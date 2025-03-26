
# Project Title

A brief description of what this project does and who it's for


## Installation

Install my-project with npm

```bash
  npm Install
  npm Install -f
  cd my-project
```
    
## API Reference

#### Get all items

```http
  GET /api/user
```

| Parameter | Type     | Description                |
| :-------- | :------- | :------------------------- |
| `api_key` | `string` | **Required**. Your API key |

#### Get item

```http
  GET /api/items/${id}
```

| Parameter | Type     | Description                       |
| :-------- | :------- | :-------------------------------- |
| `id`      | `string` | **Required**. Id of item to fetch |

#### add(num1, num2)

Takes two numbers and returns the sum.

