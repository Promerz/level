package work1;

import java.io.IOException;
import java.net.*;

public class Client {
	public static void main(String[] args) {
		Socket socket = new Socket();  // 实例化客户端的套接字
		InetSocketAddress isa = new InetSocketAddress("127.0.0.1",2018);
		try {
			socket.connect(isa); // 将客户端的套接字和服务器的套接字链接起来
			System.out.println(socket.getInetAddress()); // 输出套接字连接的地址
			System.out.println(socket.getPort());  // 输出套接字链接的端口
			System.out.println(socket.getLocalSocketAddress()); // 输出套接字绑定的本地地址
			System.out.println(socket.getLocalPort()); // 输出此套接字绑定到的本地端口
			socket.close();
		} catch (IOException e) {
			System.out.println("链接服务器异常");
		}
	}

}
