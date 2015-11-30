OBJFILES = main.o

CXXFLAGS = -Wall -std=c++0x -pipe -g
LDFLAGS  = -g
TARGET   = deep-immersion

LD       = g++
CXX      = g++

$(TARGET): $(OBJFILES)
	$(LD) $(LDFLAGS) $(OBJFILES) -o $(TARGET)
	
.PHONY: clean
clean:
	-rm -f $(OBJFILES)
	-rm -f $(TARGET)
.PHONY: default
default: all

.PHONY: all
all: $(TARGET)
