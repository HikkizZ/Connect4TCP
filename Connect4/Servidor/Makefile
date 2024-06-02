# Makefile para el servidor del juego Cuatro en Línea

CXX = g++
CXXFLAGS = -std=c++11 -Wall -Wextra -pthread
TARGET = server

all: $(TARGET)

$(TARGET): server.cpp
	$(CXX) $(CXXFLAGS) server.cpp -o $(TARGET)

clean:
	rm -f $(TARGET)
