SRC=thesis-brief
all:
	@rubber --pdf $(SRC)
x:
	okular $(SRC).pdf &> /dev/null &
clean:
	@rubber --clean $(SRC)
distclean: clean
	@rubber --clean --pdf $(SRC)
