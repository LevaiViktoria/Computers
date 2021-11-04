# computers

> Első Web Service

A web service szolgáltatásai

1. Minden számítógép
   -Method : GET 
   -url: http://localhost:8080/computers
   
2.Egy számítógép serial number alapján
    -Method : GET
    -url: http://localhost:8080/computers{id}

3.Számítógépek egy gyártótól
-Method : GET
-url: http://localhost:8080/computers{manufacture}

4.Új számítógépek felvétele
-Method : POST
-url: http://localhost:8080/computers

5.Számítógépek törlése serial number alapján
-Method : DELETE
-url: http://localhost:8080/computers{id}

6.
-Method : PATCH
-url: http://localhost:8080/computers{id}/{ram}

7.
-Method : DELETE
-url: http://localhost:8080/computers{id}



**Metódusok**
- GET
    - http://localhost:8080/computers
    - http://localhost:8080/computers/{id}
    - http://localhost:8080/computers/{manufacture}

Entity

| serial | manufacture | RAM | madein |
| :---- | :----: | ----: | :----: |
| 100 | IBM | 2 | Taivan |

*Minden jog fenntartva*