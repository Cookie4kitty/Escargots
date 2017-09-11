<<<<<<< HEAD
//线程不安全
public class HelloWorld{
	private static HelloWorld instance;
	private HelloWorld(){}
	public static HelloWorld getInstance(){
	if(instance == null){
		instance = new HelloWorld();
	}
	return instance;
	}
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
