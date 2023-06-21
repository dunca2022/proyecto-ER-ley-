consulta.py
import sqlite3
conexion = sqlite3.connect('basedatos.db')
conexion.execute('''
    CREATE TABLE IF NOT EXISTS consulta (
        N° de consulta INTEGER PRIMARY KEY,
        palabra clavde TEXT,
        N° ley 20.744 TEXT, (ESTABLECER LOS PRESUPUESTOS LEGALES MINIMOS PARA LA REGULACION DE LA MODALIDAD DE TELETRABAJO EN AQUELLAS ACTIVIDADES, QUE POR SU NATURALEZA Y PARTICULARES CARACTERISTICAS LO PERMITAN.)
        N° ley 27.555 TEXT, (REGULA LAS RELACIONES LABORALES DE LOS TRABAJADORES QUE SE ENCUENTRAN BAJO RELACION DE DEPENDENCIA, INDICA  CUALES SON LAS CARACTERISTICAS QUE DEBE REUNIR UN CONTRATO LABORAL.)
        N° ley 7642 TEXT,   (DETERMINA LAS CONDICIONES PARA EL EJERCICIO PROFESIONAL DE CIENCIAS INFORMÁTICAS, CONSTITUYE EL CONSEJO PROFESIONAL DE CIENCIAS INFORMÁTICAS DE LA PROVINCIA DE CÓRDOBA, DETERMINA UN CÓDIGO DE ÉTICA (DEBERES PARA PROFESIONALES Y PARA CLIENTES).
    )
''')
N° de consultas de leyes INTEGER PRIMARY KEY, = input("Ingrese el N° de consultas: ")
N° leyes 20.744= input("Ingrese numero de leyes: ")
N° leyes 27.555= input("Ingrese numero de leyes: ")
N° leyes 7.642= input("Ingrese numero de leyes)
conexion.execute('INSERT INTO usuarios (dni, nombre, apellido, telefono, correo) VALUES (?, ?, ?, ?)', (dni, nombre, apellido, telefono, correo))
conexion.commit()
conexion.close()
