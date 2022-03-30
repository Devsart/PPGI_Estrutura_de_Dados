# Makefile for use with mono with multiple compilation targets
#
# Prof. Gilberto - Estrutura de Dados
# 03/2022
#

CSHARP = mcs
MAIN_CLASS = Teste.cs
PARTIAL_CLASSES = SelectionSort.cs InsertionSort.cs
OPT = -optimize+

all:
	$(CSHARP) $(OPT) $(MAIN_CLASS) $(PARTIAL_CLASSES)

clean:
	rm *.exe