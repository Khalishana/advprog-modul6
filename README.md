## Commit 1 Reflection Notes
handle_connection method yang terdapat pada rust berfungsi membaca HTTP request dan me-return output berupa keterangan dan informasi HTTP request tersebut. Method ini menggunakan 
```TcpStream``` dan ```BufReader``` untuk melakukan pembacaan yang efisien. Pada akhir kode, terdapat line ```println!("Request: {:#?}", http_request);``` yang akan mengembalikan output
http_request 

## Commit 2 Reflection Notes
![Commit 2 screen capture](hello_rust.jpg)
Perubahan yang kita lakukan pada ```handle_function``` memungkinkan web server terkait dapat membuka file html yang bersesuaian dengan kode pada ```hello.html```. Pada modifikasi yang dilakukan pada file ```main.rs```, penambahan modul ```fs``` memungkinkan Rust untuk berinteraksi dengan file lain, dalam hal ini file html. Selain itu pada akhir kode, terdapat line ```stream.write_all(response.as_bytes()).unwrap();``` yang berfungsi mengirim kembali respons ke dalam urutan byte