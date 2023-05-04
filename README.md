# ginmid (gin middleware)

## Installation

```bash
go get -u github.com/metadiv-io/ginmid
```

## Highlights

* ginmid.Cache(duration time.Duration, handler gin.HandlerFunc) gin.HandlerFunc

* ginmid.CORS(config cors.Config) gin.HandlerFunc

* RateLimited(duration time.Duration, rate int64) gin.HandlerFunc
