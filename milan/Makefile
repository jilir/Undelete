CXXFLAGS =	-O2 -g -mwindows -Wall -fmessage-length=0

OBJS =		milan.o

LIBS =

TARGET =	milan.exe

$(TARGET):	$(OBJS)
	$(CXX) -o $(TARGET) $(OBJS) $(LIBS)

all:	$(TARGET)

clean:
	rm -f $(OBJS) $(TARGET)
