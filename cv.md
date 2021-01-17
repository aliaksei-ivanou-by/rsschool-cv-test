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

## Education
* BELARUSIAN STATE UNIVERSITY
    * BS in Radiophysics, Satellite information systems and technology<br/>
    Average GPA : 6.61 / 10.0<br/>
    September 2007 – July 2012 | Minsk, Belarus
* SAMARA STATE AEROSPACE UNIVERSITY
    * Summer Space School | 3.5 ECTS | August 2011 | Samara, Russia
    * Summer Space School | 3.5 ECTS | August 2013 | Samara, Russia
* MOSCOW STATE UNIVERSITY
    * Youth Scientific School<br/>
    October 2009 | Kostroma, Russia
    * Short practice<br/>
    November 2009 – December 2009 | Moscow, Russia
    * Youth conference with elements of scientific school<br/>
    March 2011 – April 2011 | Moscow, Russia

## Courses
* С++
    * С++ Programming<br/>
    March 2018 – May 2018 | Minsk, Belarus
    * C++ Development Fundamentals: White Belt<br/>
    February 2020 – March 2020 | Minsk, Belarus
    * C++ Development Fundamentals: Yellow Belt<br/>
    March 2020 – … | Minsk, Belarus
    * C++ EPAM Mentoring Program<br/>
    May 2020 – … | Minsk + Brest, Belarus
* LaTeX
    * Documents and presentations in LaTeX (Introduction to LaTeX)<br/>
    May 2016 – June 2016 | Minsk, Belarus
* Ruby
    * Building web applications with Ruby on Rails (course.by)<br/>
    February 2015 – June 2015 | Minsk, Belarus
* JAVA
    * Java. JD1. Programming in Java<br/>
    October 2012 – December 2013 | Minsk, Belarus
* LabVIEW
    * LabVIEW – Basics I<br/>
    December 2010 | Minsk, Belarus
    * LabVIEW – Data Acquisition<br/>
    January 2011 | Minsk, Belarus

## English language
Current level of English is A2+.
* A1. Elementary level
    Exam : 98 / 100<br/>
    September 2015 – December 2015 | Minsk, Belarus
* A2. Pre-Intermediate level
    Exam : 98 / 100<br/>
    January 2016 – May 2016 | Minsk, Belarus
* B1. Intermediate level
    Exam : 82 / 100<br/>
    September 2016 – December 2016 | Minsk, Belarus
* B2. Upper-Intermediate level
    Exam : 60.5 / 100<br/>
    January 2017 – May 2017 | Minsk, Belarus
