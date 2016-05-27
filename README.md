class building()
{
double area;
double volume;
double costofconstruction;
}
class building1 extends building()
{
string paintcolor;window material;
}
class building2 extends building()
{
double paintcost;
door material;
}
building1.area=300sq.km;
building2.volume=280ccm;
building1.paintcolor="red";
building2.material="glass";
system.out.println("building1.area,building1.paintcolor" +building1.area ,+building1.paintcolor);
system.out.println("building2.volume,building2.material" +building2.volume ,+building2.material);
}
}
