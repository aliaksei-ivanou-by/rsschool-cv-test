# Aliaksei Ivanou
---
## Contacts
* Phone: [+375 29 559 85 56](tel:+375295598556)
* Mobile : +375 29 559 85 56
* Skype : aliaksei.ivanou
* E-mail : aliaksei.ivanou.by@icloud.com
* [GitHub](https://github.com/aliaksei-ivanou-by) | [LinkedIn](https://www.linkedin.com/in/aliaksei-ivanou-by/) | [Facebook](https://www.facebook.com/100009630485315)

## About
Currently I learn C++ at the mentoring program at EPAM Systems, Inc. Before this I've been working for a 7.5 years as the R&D Engineer in space industry in the projects "Belarussian Spacecraft”, “EgyptSat-2”, “EgyptSat-A”, “Obzor-O”, satellites series “Kanopus-V”, optical system for UAV.

## Skills
MATLAB • C++ • LaTeX • Ruby • JAVA • LabVIEW • System Tool Kit<br/>
Digital Signal Processing • Aerospace Technologies • Satellites • UAV • Remote Sensing

## Code Samples
```
#include "iostream"
class Base
{
public:
	Base() { std::cout << "Base created" << std::endl; }
	virtual ~Base() { std::cout << "Base destroyed" << std::endl; }
	virtual void foo1() { std::cout << "Base::foo1" << std::endl; }
	void foo2() { std::cout << "Base::foo2" << std::endl; }
};
class Child : public Base
{
public:
	Child() { std::cout << "Child created" << std::endl; }
	~Child() { std::cout << "Child destroyed" << std::endl; }
	void foo1() { std::cout << "Child::foo1" << std::endl; };
	void foo2() { std::cout << "Child::foo2" << std::endl; };
};
void process1(Base* obj)
{
	std::cout << "In process1" << std::endl;
	obj->foo1();
	obj->foo2();
}
void process2(Base obj)
{
	std::cout << "In process2" << std::endl;
	obj.foo1();
	obj.foo2();
}
int main()
{
	Base* p = new Child;
	std::cout << '\n';
	process1(p);
	std::cout << '\n';
	process2(*p);
	std::cout << '\n';
	delete p;
	return 0;
}
```
