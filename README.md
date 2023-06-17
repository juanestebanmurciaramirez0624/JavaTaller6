En el taller 6 java web se creó un archivo. java con el nombre Repository este archivo es una interfaz es decir que en este archivo se crearán los métodos pero no se implementaron, también se hace uso de java generics por medio de la etiqueta <T> la cual permite que la interfaz sea capaz de recibir cualquier objeto, en la interfaz se crean los métodos ListAll, ByIdObj, SaveObje, DeleteObj y CreateObj, Igualmente se crea el archivo UserRepositoryImpl.java el cual es una clase en la que se implementa la interfaz Repository con sus respectivos métodos el método ListAll nos permite realizar una consulta de todos los datos de los usuarios en la BD, el metodo ByIdObj nos permite realizar la consulta de un solo usuario en la BD, el método SaveObj nos permite tanto insertar un usuario en la BD como actualizar los datos de un usuario ya existente, el método deleteObj nos permite eliminar a un usuario de la BD y finalmente el método CreateObj nos permite como su nombre lo indica crear los objetos en la BD con sus respectivos datos, para finalizar también se creo el archivo testRepositoryImpl.java en el cual se utilizan todos los métodos al crear objetos (usuarios), realizar consultas de todos o de un solo usuario, actualizar datos e eliminar datos 

Se adjunta capturas de pantallas de: 

1. Las vistas login y formulario de registro de usuarios
![logincaptura](https://github.com/juanestebanmurciaramirez0624/JavaTaller6/assets/116554534/ad8195b2-3c64-4d41-b49e-382e6434acad)
![FormularioRegistrocaptura](https://github.com/juanestebanmurciaramirez0624/JavaTaller6/assets/116554534/00b030e3-7d8d-4fee-8b8d-74c18f127f43)

2. El Test de reposiotorio de forma funcional asi como una captura de una consulta de la tabla usuario para comprobar
![TestFuncioanalcaptura](https://github.com/juanestebanmurciaramirez0624/JavaTaller6/assets/116554534/fe490aef-182b-414c-a417-941faf2d016e)
![ConsultaBDTestcaptura](https://github.com/juanestebanmurciaramirez0624/JavaTaller6/assets/116554534/76bc67ec-5632-40eb-964f-175a0ccf1206)

3. El connection pool de forma funcional
![ConnectionPoolFuncionalcaptura](https://github.com/juanestebanmurciaramirez0624/JavaTaller6/assets/116554534/e810ba3e-8ccc-4821-8649-1264ae1043a9)



