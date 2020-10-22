# CRUD.JAVA-MYSQL
Ejecuciòn de aplicaciòn con netbeans 8.2 de crud en tablas mysql
COMPARTO ES SCRIPT DE LA TABLA DEL EJEMPLO DE LA APLICACIÒN, LA BASE DE DATOS LA PUEDEN LLAMAR COMO QUIERA Y ANEXAN LA TABLA.

CREATE TABLE `ws_reglaboral_informes` (
  `Rlab_Identific_informes` bigint(20) NOT NULL,
  `Rlab_EmpNit_informes` int(10) NOT NULL DEFAULT 1,
  `Rlab_ContrNit_informes` bigint(20) NOT NULL,
  `Rlab_Obranit_informes` bigint(20) NOT NULL,
  `Rlab_FechaIngreso_informes` date NOT NULL,
  `Rlab_HoraIngresoIni_informes` time NOT NULL,
  `Rlab_HoraSalidaFin_informes` time NOT NULL,
  `Rlab_DiaLaborado_informes` tinyint(3) NOT NULL,
  `Rlab_timeLabor_informes` time NOT NULL,
  `Rlab_temp` float DEFAULT NULL,
  `Rlab_temp_dat` float DEFAULT NULL,
  PRIMARY KEY (`Rlab_Identific_informes`,`Rlab_FechaIngreso_informes`,`Rlab_HoraIngresoIni_informes`)
) ENGINE=InnoDB DEFAULT CHARSET=latin1;
