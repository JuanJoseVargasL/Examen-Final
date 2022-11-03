# Examen-Final
import java.util.Arrays;
public class Agentemercado {
public Agentemercado(int id, String nombre, PlantaGeneracion[] plantasGeneracion, String ciudad, String presidente,
			double dinerodisponible) {
		super();
		this.id = id;
		this.nombre = nombre;
		this.plantasGeneracion = plantasGeneracion;
		this.ciudad = ciudad;
		this.presidente = presidente;
		Dinerodisponible = dinerodisponible;
	}
private int id;
private String nombre;
private PlantaGeneracion[] plantasGeneracion;
private String ciudad;
private String presidente;
private double Dinerodisponible;
public int getId() {
	return id;
}
public void setId(int id) {
	this.id = id;
}
public String getNombre() {
	return nombre;
}
public void setNombre(String nombre) {
	this.nombre = nombre;
}
public PlantaGeneracion[] getPlantasGeneracion() {
	return plantasGeneracion;
}
public void setPlantasGeneracion(PlantaGeneracion[] plantasGeneracion) {
	this.plantasGeneracion = plantasGeneracion;
}
public String getCiudad() {
	return ciudad;
}
public void setCiudad(String ciudad) {
	this.ciudad = ciudad;
}
public String getPresidente() {
	return presidente;
}
public void setPresidente(String presidente) {
	this.presidente = presidente;
}
public double getDinerodisponible() {
	return Dinerodisponible;
}
public void setDinerodisponible(double dinerodisponible) {
	Dinerodisponible = dinerodisponible;
}

public String mostrarDatos () {
	return "Agentemercado [id=" + id + ", nombre=" + nombre + ", plantasGeneracion="
			+ Arrays.toString(plantasGeneracion) + ", ciudad=" + ciudad + ", presidente=" + presidente
			+ ", Dinerodisponible=" + Dinerodisponible + "]";
}


}
import java.util.Arrays;
public class segundaparte {
public segundaparte(int id, String recurso, String ciudad, String fechaInicial, String[] fechasMantenimiento,
			double factordeDisponibilidad, double presupuestoMantenimiento) {
		super();
		this.id = id;
		this.recurso = recurso;
		this.ciudad = ciudad;
		this.fechaInicial = fechaInicial;
		this.fechasMantenimiento = fechasMantenimiento;
		this.factordeDisponibilidad = factordeDisponibilidad;
		this.presupuestoMantenimiento = presupuestoMantenimiento;
	}
private int id;
private String recurso;
private String ciudad;
private String fechaInicial;
private String fechasMantenimiento[];
private double factordeDisponibilidad;
private double presupuestoMantenimiento;
public int getId() {
	return id;
}
public void setId(int id) {
	this.id = id;
}
public String getRecurso() {
	return recurso;
}
public void setRecurso(String recurso) {
	this.recurso = recurso;
}
public String getCiudad() {
	return ciudad;
}
public void setCiudad(String ciudad) {
	this.ciudad = ciudad;
}
public String getFechaInicial() {
	return fechaInicial;
}
public void setFechaInicial(String fechaInicial) {
	this.fechaInicial = fechaInicial;
}
public String[] getFechasMantenimiento() {
	return fechasMantenimiento;
}
public void setFechasMantenimiento(String[] fechasMantenimiento) {
	this.fechasMantenimiento = fechasMantenimiento;
}
public double getFactordeDisponibilidad() {
	return factordeDisponibilidad;
}
public void setFactordeDisponibilidad(double factordeDisponibilidad) {
	this.factordeDisponibilidad = factordeDisponibilidad;
}
public double getPresupuestoMantenimiento() {
	return presupuestoMantenimiento;
}
public void setPresupuestoMantenimiento(double presupuestoMantenimiento) {
	this.presupuestoMantenimiento = presupuestoMantenimiento;
}

public String mostrarDatos() {
	return "segundaparte [id=" + id + ", recurso=" + recurso + ", ciudad=" + ciudad + ", fechaInicial=" + fechaInicial
			+ ", fechasMantenimiento=" + Arrays.toString(fechasMantenimiento) + ", factordeDisponibilidad="
			+ factordeDisponibilidad + ", presupuestoMantenimiento=" + presupuestoMantenimiento + "]";
}


}
