<<<<<<< HEAD
<<<<<<< HEAD
//�̲߳���ȫ
=======
# Escargots
>>>>>>> parent of 521b926... HelloWorld
public class HelloWorld{
	private static HelloWorld instance;
	private HelloWorld(){}
	public static HelloWorld getInstance(){
	if(instance == null){
		instance = new HelloWorld();
	}
	return instance;
	}
<<<<<<< HEAD
}

//�̰߳�ȫ
public class HelloWorld{
	private static HelloWorld instance;
	private HelloWorld(){}
	public static synchronized HelloWorld getInstance(){
	if(instance == null){
		instance = new HelloWorld();
		}
	return instance;
	}
}


=======
# Escargots
Test
>>>>>>> parent of c86d36c... Simple Singleton Instance
=======
}
>>>>>>> parent of 521b926... HelloWorld
