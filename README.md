class simpleinterest2
{
    int p,t;
    double r,ans;//instance variables
    void init()//non-interactive input
    {
        p=2000;
        t=2;
        r=3.5;
        //System.out.println(ans);
    }
    void calc()
    {
        ans=(p*r*t)/100;
    }
    void display()
    {
        System.out.println(ans);
    }
}
