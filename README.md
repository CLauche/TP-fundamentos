# TP-fundamentos
ejercicios del TP final de Fundamentos de informática

#Ejercicio 1-Elemento

class Elemento:
    def __init__(self,numeroAtomico,cantNeutrones,simbolo,valencia):
        self.__numeroAtomico = numeroAtomico
        self.__simbolo = simbolo
        self.__valencia = valencia
        self.__cantNeutrones = cantNeutrones

    def cantElectrones(self):
        return self.__numeroAtomico

    def cantProtones(self):
        return self.__numeroAtomico

    def pesoAtomico (self):
        return self.__numeroAtomico + self.__cantNeutrones


# para cada elemento agregado se ingresa la cantidad de neutrones que posee,/
# de manera de facilitar el cálculo del pesoAtomico
# El dato de valencia lo tomé de https://www.ptable.com/?lang=es#Property/State

oxigeno = Elemento(8,8,'O',2)
hidrogeno = Elemento (1,0,'H',1)
nitrogeno = Elemento(7,7,'N',5)
carbono = Elemento (6,6,'C',4)
azufre = Elemento (16,16,'S',6)


#Ejercicio 2-Tabla Periódica

import Elemento

class Tabla_Periodica:
    def __init__(self):
        super().__init__()
        self._Elemento = Elemento

#inicialmente planteé que la clase Tabla_Periodica hereda las propiedades
# y los métodos de la clase Elemento


    def agregar_elemento(self, Elemento):
        return self.list.append(Elemento)

    def elementos_agregados(self):
        return list (self)

    def elementoS(self, Elemento):
        for Elemento in self:
            return simbolo
        else:
            return 'None'

    def elementoN(self, Elemento):
        for Elemento in self:
            return Elemento._numeroAtomico
        else:
            return 'None'
