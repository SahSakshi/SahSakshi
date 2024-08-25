- #include<iostream>
#include<string>
using namespace std;
class teacher{
   public:
   teacher(string name,string subject,double salary){
    this->name = name;
    this->subject = subject;
    this->salary = salary;
   }
  string name;
  string subject;
  double salary;
  teacher(teacher &orgOb){
   this->name = orgOb.name;
   this->subject = orgOb.subject;
   this->salary = orgOb.salary; 
  }
  void getinfo(){
    cout<<"name:"<<name<<endl;
    cout<<"subject:"<<subject<<endl;
    cout<<"salary:"<<salary<<endl;
  }
};
int main(){
  teacher t1("sakshi","c++",34000);
  t1.getinfo();
  teacher t2(t1);
  t2.getinfo();
  return 0;
}👋 Hi, I’m @SahSakshi
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...

<!---
SahSakshi/SahSakshi is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
