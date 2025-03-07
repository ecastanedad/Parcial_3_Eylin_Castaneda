# Ejemplo 1
class Empleado:
    def __init__(self, nombre, salario):
        self.nombre = nombre
        self.salario = salario

    def mostrar_informacion(self):
        return f"Empleado: {self.nombre}, Salario: {self.salario}"

    def aumentar_salario(self, porcentaje):
        self.salario += self.salario * (porcentaje / 100)
        return f"Nuevo salario de {self.nombre}: {self.salario}"

if __name__ == "__main__":
    empleado1 = Empleado("Ana López", 60000)
    print(empleado1.mostrar_informacion())
    print(empleado1.aumentar_salario(15))

# Ejemplo 2
class Empleado:
    def __init__(self, nombre, salario):
        self.nombre = nombre
        self.salario = salario

    def mostrar_informacion(self):
        return f"Empleado: {self.nombre}, Salario: {self.salario}"

    def aumentar_salario(self, porcentaje):
        self.salario += self.salario * (porcentaje / 100)
        return f"Nuevo salario de {self.nombre}: {self.salario}"

if __name__ == "__main__":
    empleado1 = Empleado("Ana López", 60000)
    print(empleado1.mostrar_informacion())
    print(empleado1.aumentar_salario(15))
