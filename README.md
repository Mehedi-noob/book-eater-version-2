# book eater Backend

## Live link: https://book-catalog-version-2.vercel.app

## API Routes:

## User Routes

- `/api/v1/auth/signup` (POST)
- `/api/v1/users` (GET)
- `/api/v1/users/7cb85a5e-1363-4ae4-be70-10ac788cfbe2` (Single GET)
- `/api/v1/users/7cb85a5e-1363-4ae4-be70-10ac788cfbe2` (PATCH)
- `/api/v1/users/9fd1411c-a3ce-46df-8af1-39c2e25bfa6b` (DELETE)
- `/api/v1/profile` (GET)

## Category Routes

- `/api/v1/categories/create-category` (POST)
- `/api/v1/categories` (GET)
- `/api/v1/categories/cff02fcf-84d5-4269-b27b-a3032e190ce0` (Single GET)
- `/api/v1/categories/cff02fcf-84d5-4269-b27b-a3032e190ce0` (PATCH)
- `/api/v1/categories/cff02fcf-84d5-4269-b27b-a3032e190ce0` (DELETE)

## Books Routes

- `/api/v1/books/create-book` (POST)
- `/api/v1/books` (GET)
- `/api/v1/books/:categoryId/category` (GET)
- `/api/v1/books/e9704d87-d166-4594-8589-b35b5aaff0aa` (GET)
- `/api/v1/books/e9704d87-d166-4594-8589-b35b5aaff0aa` (PATCH)
- `/api/v1/books/e9704d87-d166-4594-8589-b35b5aaff0aa` (DELETE)

## Orders Routes

- `/api/v1/orders/create-order` (POST)
- `/api/v1/orders` (GET)
- `/api/v1/orders/6d035e90-d97e-4483-8deb-0fc8899da10c` (GET)
