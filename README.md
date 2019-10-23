
void main() {
 Conta c = new Conta(1235,2541,5000);
  c.deposito(1000);
  c.transferencia(200);
  c.saque(50);
}
class Conta{
  int conta;
  int agencia;
  double saldo;
  Conta(this.conta,this.agencia,this.saldo);
  void transferencia(double a){
    if(this.saldo<a){
      print("Saldo insuficiente");
    }
    else{
      this.saldo = this.saldo - a;
      saldoatual();
    }
  
  }
  void saldoatual(){
    print("saldo atual é ${this.saldo}");
  }
  void deposito(double d){
    this.saldo = this.saldo + d;
    saldoatual();
  }
  void saque(double saque){
      if(this.saldo<saque){
      print("Saldo insuficiente");
    }
    else{
      this.saldo = this.saldo - saque;
      saldoatual();
    }
  }
}
