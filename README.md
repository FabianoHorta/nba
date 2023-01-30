
# Projeto Módulo 4 (Banco de Dados NBA) 

Montagem de um dashboard com base no conjunto de banco de dados disponibilizado pela Resilia. O banco de dados escolhido foi NBA.

Utilizamos:
Power BI, Excel, MySQL e Xampp.

Consultas:
Arena com maior capacidade?
![SELECT MAX ('ARENACAPACITY') FROM times](https://github.com/FabianoHorta/nba/blob/44de49a575aa03190268dec30ce8ef4c0ea79086/prints%20das%20requisi%C3%A7%C3%B5es/arena%20com%20maior%20capacidade.png)

Cidade com mais times registrados?
![SELECT * FROM times WHERE CITY LIKE 'L%'](https://github.com/FabianoHorta/nba/blob/44de49a575aa03190268dec30ce8ef4c0ea79086/prints%20das%20requisi%C3%A7%C3%B5es/cidade%20los%20angeles.png)

Proprietários dos times?
![SELECT OWNER FROM times ORDER BY DESC](https://github.com/FabianoHorta/nba/blob/44de49a575aa03190268dec30ce8ef4c0ea79086/prints%20das%20requisi%C3%A7%C3%B5es/propriet%C3%A1rio%20dos%20times%20parte%201.png)


Times mais antigo?
![SELECT MIN ('MIN_YEAR') AS time_mais_antigo FROM times](https://github.com/FabianoHorta/nba/blob/44de49a575aa03190268dec30ce8ef4c0ea79086/prints%20das%20requisi%C3%A7%C3%B5es/time%20mais%20antigo.png)


Time mais novo?
![SELECT MAX ('MIN_YEAR') AS time_mais_novo FROM times](https://github.com/FabianoHorta/nba/blob/44de49a575aa03190268dec30ce8ef4c0ea79086/prints%20das%20requisi%C3%A7%C3%B5es/time%20mais%20novo.png)

Diagrama:
Modelo relacional NBA.

Grupo:
Alvaro de Paula, Fabiano Almeida, Ramon Carvalho, Victor Soares, Yasmin Carregal.
