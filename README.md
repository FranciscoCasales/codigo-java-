# Patron de diseño proxy
## El patrón de diseño proxy su principal función y propósito es proporcionar un intermediario para poder gestionar el creado de objetos en el momento necesario. Esto permite la seguridad y la    administración de los recursos, la mayoria de las veces cuando se usa este patrón de diseño es para objetos que son muy costosos para su creación(recursos y tiempo).
## Ventajas: * Es muy bueno la para la seguridad * No se crea ningún objeto hasta que sea necesario
## Desventajas : * Se debe saber especificamente que objetos administrara el proxy   * Si existe una alta concurrecia hacia los objetos que administra el proxy esto haría lento el systema.