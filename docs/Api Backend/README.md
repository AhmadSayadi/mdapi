# Api Backend


## login

**Method:** ```POST```

**URL:** ```/```

**Body**

```
{
    "username":"admin",
    "password":"admin"
}
```
## login Copy

**Method:** ```POST```

**URL:** ```/```

**Body**

```
{
    "username":"admin",
    "password":"admin"
}
```
## Create Product

**Method:** ```POST```

**URL:** ```/```

**Body**

```
{
    "nama":"kripik",
	"harga":"100000",
	"satuan":"10000",
	"qty":2,
	"minbeli":2,
	"maxbeli":2,
	"stok":2
}
```
## Produc By ID

**Method:** ```GET```

**URL:** ```/```
## Product Update

**Method:** ```POST```

**URL:** ```/```

**Body**

```

{
	"nama":"Satu aya",
	"harga":"100000",
	"satuan":"10000",
	"qty":"2",
	"minbeli":100,
	"maxbeli":100,
	"stok":100
}
```
## Delete Product

**Method:** ```DELETE```

**URL:** ```/```
## All Product

**Method:** ```POST```

**URL:** ```/```

**Body**

```

{
    "start": "0",
    "length": "10",
    "order": [ { "column": "0", "dir": "asc" } ],
    "search": {
        "value": "gre", 
        "regex": "false"
    }
}

```
## All Product Copy

**Method:** ```POST```

**URL:** ```/```

**Body**

```

{
    "start": "0",
    "length": "10",
    "order": [ { "column": "0", "dir": "asc" } ],
    "search": {
        "value": "gre", 
        "regex": "false"
    }
}

```
## All Product Copy

**Method:** ```GET```

**URL:** ```/side1```

**Query Parameters:**

You can include the following parameters in a search request.

| Key | Value | Description |
| --- | --- | --- |
| page | 3 |  |
| size | 10 |  |
| search |  |  |

## profile

**Method:** ```GET```

**URL:** ```/```
## User By ID

**Method:** ```GET```

**URL:** ```/```
## all user

**Method:** ```GET```

**URL:** ```/```
## faker

**Method:** ```POST```

**URL:** ```/```
## New Request

**Method:** ```GET```

**URL:** ```/```
