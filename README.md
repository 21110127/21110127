- 👋 Hi, I’m @21110127
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...
- //tarea 5 odjetos de saul alexander alba garcia 21110127
#include <iostream>
#include <stdlib.h>
using namespace std;
class persona{
    	private:
    		int edad;
    		string nombre;
    	public:
    		persona(int,string);
    			void leer();
    			void correr();
	}
persona::persona(int _edad,string _nombre){
	edad = _edad;
	nombre = _nombre;	 
}
void persona::leer()
{
	cout<<"soy "<<nombre << " y estoy leyendo un libro y tengo "<<edad<<" anos";
}
void persona::correr()
{
	cout<<"soy "<<nombre << " y estoy leyendo un libro y tengo "<<edad<<" anos";
}


int main()
{
	persona p1(25,"jesus");
	persona p2 (19,"octavio");
	persona p3 (18,"miguel");
	persona p4 (19,"rosa");
	persona p5 (22,"rogelio");
	
	p1.leer();
	p2.leer();
	p3.correr();
	p4.leer();
	p5.correr();
	
	
   system("pause");
   return 0:
}
