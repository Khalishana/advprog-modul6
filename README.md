## Commit 1 Reflection Notes
handle_connection method yang terdapat pada rust berfungsi membaca HTTP request dan me-return output berupa keterangan dan informasi HTTP request tersebut. Method ini menggunakan 
```TcpStream``` dan ```BufReader``` untuk melakukan pembacaan yang efisien. Pada akhir kode, terdapat line ```println!("Request: {:#?}", http_request);``` yang akan mengembalikan output
http_request 
