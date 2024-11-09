SRC = Acc.cpp Main.cpp NewUser.cpp Message.cpp Chat.cpp Server.cpp UserRepository.cpp Socket.cpp
TARGET = chats
PREFIX = /home/server/cliser/srvr

chats: $(SRC)
	g++ -o $(TARGET) $(SRC)

clean:	
	rm -rf *.o *.a

install:
	install $(TARGET) $(PREFIX)

uninstall:	
	rm -rf $(PREFIX)/$(TARGET)

