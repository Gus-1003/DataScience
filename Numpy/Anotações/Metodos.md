# Métodos Aplicados:

np.array = cria uma matriz
* Link = https://numpy.org/doc/stable/reference/generated/numpy.array.html


np.arange = Retorne valores espaçados uniformemente dentro de um determinado intervalo.

* Link = https://numpy.org/doc/stable/reference/generated/numpy.arange.html


np.reshape = Dá uma nova forma a uma matriz sem alterar seus dados.

* Link = https://numpy.org/doc/stable/reference/generated/numpy.reshape.html

np.ndim = o número de eixos (dimensões) da matriz.

np.shape = Retorna o valor que representa o tamanho de cada dimensão da matriz.

np.size = 
o número total de elementos da matriz. Isso é igual ao produto dos elementos de .shape

np.dtype = 
um objeto descrevendo o tipo de elementos na matriz. Pode-se criar ou especificar dtype's usando tipos Python padrão. Além disso, a NumPy fornece tipos próprios. numpy.int32, numpy.int16 e numpy.float64 são alguns exemplos.

np.itemsize = 
o tamanho em bytes de cada elemento da matriz. Por exemplo, uma matriz de elementos do tipo tem 8 (=64/8), enquanto um do tipo tem 4 (=32/8). É equivalente a.float64itemsizecomplex32itemsizendarray.dtype.itemsize

np.data = 
o buffer contendo os elementos reais da matriz. Normalmente, não precisaremos usar esse atributo porque acessaremos os elementos em uma matriz usando instalações de indexação.
