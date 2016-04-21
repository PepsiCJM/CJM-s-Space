# CJM-s-Space
My first GitHub repository ~ !
Class My {

  private:
    int num;
    
  public:
    void SetNum(int aaa){
      num = aaa;
    }
    int GetNum(){
      retrn num;
    }
    
};

void main(){

  int num;
  My my();
  cin>>num;
  my.SetNum(num);
  num = my.GetNum();
  cout<<num<<endl;

}
