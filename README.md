Secuencia: Cambio de Aceite

Cliente -> Automóvil: Solicita cambio de aceite
Automóvil --> Técnico de servicio: Llega al taller
Técnico de servicio -> Servicio de cambio de aceite: Inicia el servicio

ActivarTemporizador(30 minutos)

loop while (Temporizador no ha alcanzado 30 minutos):
    Técnico de servicio -> Automóvil: Drena el aceite viejo
    Técnico de servicio -> Automóvil: Reemplaza el filtro de aceite
    Técnico de servicio -> Automóvil: Llena con aceite nuevo

Técnico de servicio -> Automóvil: Termina el servicio
Técnico de servicio --> Cliente: Notifica al cliente que el servicio ha terminado

Cliente --> Automóvil: Recoge el automóvil

