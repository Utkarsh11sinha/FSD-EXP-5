# Product CRUD API (Express + Mongoose)

Basic REST API to perform CRUD operations for products using MongoDB and Mongoose.

## Requirements

- Node.js 18+
- MongoDB running locally on `mongodb://127.0.0.1:27017`

## Setup

```bash
npm install
```

## Environment

Default `.env`:

```env
PORT=5000
MONGODB_URI=mongodb://127.0.0.1:27017/productdb
```

## Run

```bash
npm run dev
```

or

```bash
npm start
```

## API Endpoints

Base URL: `http://localhost:5000/api/products`

- `POST /` - Create product
- `GET /` - Get all products
- `GET /:id` - Get single product by id
- `PUT /:id` - Update product by id
- `DELETE /:id` - Delete product by id

## Sample JSON for Create/Update

```json
{
  "name": "Wireless Mouse",
  "description": "2.4GHz ergonomic mouse",
  "price": 799,
  "quantity": 25
}
```
