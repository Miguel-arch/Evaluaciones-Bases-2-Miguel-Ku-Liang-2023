> Bases de Datos 2, Prueba corta 9  
> Miguel Ku Liang - 2019061913

# 1.

Debido a que se presenta un read-heavy workload de la cual los queries son muy diferentes, utilizar el cache no beneficiaría al sistema ya que este guarda los datos más utilizados. Al recibir queries diferentes, el cache no beneficia significativamente al sistema, incluso puede afectar negativamente al sistema ya que cuando recibe muchos datos variados, el cache se puede llenar, por lo que necesitará eliminar datos que no se han utilizado muy frecuentemente, afectando el rendimiento de los procesos que utilicen estos datos ya que tardarán más en conseguir los datos.

# 2.

Las particiones tienen menos registros que la base de datos completa, por lo que se necesita menos tiempo en recuperar la información o ejecutar una consulta, mejorando el tiempo de respuesta del sistema. También, evita la interrupción total del sistema ya que un error en una partición no afecta en el funcionamiento de las otras particiones. Las particiones permiten agregar más recursos para manejar el escalado de la base de datos. Además, se puede crear más particiones durante la ejecución sin afectar el sistema.

# 3.

Los exclusive locks se generan cuando en uno de dos o más procesos hay una operación de escritura. Este proceso bloquea los demás procesos para realizar su escritura. Este bloqueo ocasiona que los otros procesos tengan que esperar a que termine el proceso de escritura que llegó primero, por lo que el rendimiento de la base de datos baja.

# 4.

Dependiendo del disco, puede tener un alto o bajo IOPS, afectando la cantidad de datos que puede transferir por unidad de tiempo y por ello, la velocidad de procesamiento de la base de datos. Además, la latencia del disco que determina el tiempo que tarda en ejecutar una transferencia de datos. 