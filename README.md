<<<<<<< HEAD
<<<<<<< HEAD
//线程不安全
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

//线程安全
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
