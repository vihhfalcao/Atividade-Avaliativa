# Atividade-Avaliativa# 
2)a)
void main(){
int b = 3;
String nome = 'Vitória';
print(b);
print(nome);
}

2)b)
void main(){
Chamada();
}
void Chamada(){
  for(int i=1; i<=10; i++){
    print(i);
  }
}

2)c)
void main(){
 int a = 50;
Chamada(a);
}
void Chamada(int b){
  for(int i=1; i<=b; i++){
    print(i);
  }
}

2)d)
void main(){
 int a = 50;
Chamada(a);
}
void Chamada(int b){
   int c = 0;
  for(int i=0; i<=b; i++){
    c = c + i;
  }
  print(c);
}

2)e)
void main(){
Pessoa gente = new Pessoa('Fulano','Sicrano','Beltrano',10,1.70);
  gente.Fazendo();
  gente.Pensando();
  gente.nome;
  gente.pai;
  gente.mae;
  gente.idade;
  gente.altura;
  print( gente.nome);
  print( gente.pai);
  print( gente.mae);
  print( gente.idade);
  print( gente.altura);
}
class Pessoa{
  String nome;
  String pai;
  String mae;
  int idade;
  double altura;
  Pessoa(this.nome, this.pai, this.mae, this.idade, this.altura);
  void Fazendo(){
    print('Fazendo nada no  momento');
  }
  void Pensando(){
    print('Como eu queria está em casa no momento');
  }
}
