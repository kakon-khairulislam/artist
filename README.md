# artist
#include <iostream>
using namespace std;
class artist{
public :
string name;
int id;
string email;
};

int main() {
  artist art;
  art.name="kanizlub";
  art.id = 101;
  art.email= "kanafattehloop99@gmail.com";
  cout<<art.name<<"  " <<art.id<< "  " << art.email<< endl;
  return 0;
}
