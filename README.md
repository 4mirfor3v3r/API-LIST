# LIST OF REST-API 

Kumpulan rest api yang pernah saya buat

## CRUD Data Pegawai
- ### Create (POST)
    ```
    https://kotlin-rest-api.herokuapp.com/users/tambah
    ```
    - ##### body
        - nip (String)
        - nama_pegawai (String)
        - alamat_pegawai (String)
        - no_telp (String)
- ### READ (GET)
    ```
    https://kotlin-rest-api.herokuapp.com/users/getAllUsers
    ```
- ### UPDATE (PUT)
    ```
    https://kotlin-rest-api.herokuapp.com/users/edit
    ```
    - ##### TARGET (BODY)
        - _id (String)
    - ##### body
        - nip (String)
        - nama_pegawai (String)
        - alamat_pegawai (String)
        - no_telp (String)
- ### DELETE (DELETE)
    ```
    https://kotlin-rest-api.herokuapp.com/users/delete/:id
    ```
    - ##### params/path
        - _id (String)


### Todos

 - [x] DATA Pegawai
 - [ ] CHAT APP
 - [ ] etc

License
----

[MIT](https://choosealicense.com/licenses/mit/)


**Free ??, Hell Yeah!**
