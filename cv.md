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

## Work Experience
* PELENG, JSC
    * Design Engineer, Space Division
    August 2012 – December 2019 | Minsk, Belarus
        * Participation in development of optical sensors for satellites “Belarussian Spacecraft”, “EgyptSat-2”, “EgyptSat-A”, “Monitoring-SG”, “Meteor-MP”, “Obzor-O”, satellites series “Kanopus-V”, optical sensor for UAV.
        * Participation in flight tests and operation control of satellites “Belarussian Spacecraft”, “EgyptSat-2”, “EgyptSat-A”, satellites series “Kanopus-V”.
        * Participation in flight tests and operation control of optical sensor for UAV.
        * Development of image compression algorithm (ADPCM): **MATLAB**.
        * Writing the design projects.
        * Planning of shooting during the flight tests: **Systems Tool Kit**.
        * Linear resolution analysis of images of the Earth surface: **MATLAB**.
        * Correcting gauge coefficients for photomatrixes for removing any defects in target apparatus operation: **MATLAB**.
        * Development databases: **MS Access**, **Ruby on Rails**, **PostgreSQL**.
        * Development of DB of remote sensing satellites: **Ruby on Rails**, **PostgreSQL**, **Git**.
        * Development of photo/video processing algorithms (debayer algorithm, convertation of image format, stabilization algorithm, image fusion algorithm, etc): **MATLAB**.
        * Adjustment and exhibition of image sensors in one plane.
        * UAV IMU calibration: **MATLAB**.
* INFORMATION CENTER LAND CADASTRE DATA AND MONITORING OF LAND, RUE
    * Engineer, Department of navigation and information technologies
    June 2010 – May 2012 | Minsk, Belarus
        * Sales, installation and maintenance system of satellite monitoring of transport.
        * Website Development: **CMS Joomla**, **CMS Drupal**.
