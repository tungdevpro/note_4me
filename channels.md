Channels thường được sử dụng để truyền dữ liệu giữa các goroutine mà không quan tâm đến việc quản lý **locking** hoặc tránh vấn đề đua tài nguyên (race conditions)
Khai báo một channel

```go
    ch := make(chan T)
```

Trong đó T là type (int, string, array, v.v.v)
