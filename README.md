# repositorio3
public class Empleado {
    
	Employee empli1= new Employee("Aldo Barrera", 3016.68)
	double sueldo;
	String nombre;
	int afp;
	int aguinaldo;
	int quinquenio;
	int seguro;
	int sueldototal;
	public String getNombre() {
		return nombre;
	}
	public Empleado(String nombre, int afp , int aguinaldo,int quinquenio,int seguro, int sueldototal, double sueldo) {
		super();
		this.nombre = nombre;
		this.afp = afp;
		this.aguinaldo = aguinaldo;
		this.quinquenio = quinquenio;
		this.seguro  = seguro;
		this.sueldo = sueldo;
		this.sueldototal= sueldototal;
	}
	public void setNombre(String nombre) {
		this.nombre = nombre;
	}
	public void setafp(int afp) {
		this.afp = afp;
	}
	public void setaguinaldo(int aguinaldo) {
		this.aguinaldo = aguinaldo;
	}
	public void setCedula(int quinquenio) {
		this.quinquenio = quinuqenio;
	}
	public void setseguro(int seguro) {
		this.seguro = seguro;
	}
	public double getsueldo() {
		return sueldo;
	}
	public void setsueldo(double sueldo) {
		this.ueldo = sueldo;
	}
	
