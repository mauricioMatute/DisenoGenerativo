# Edificio
package paqueteDiseñoGenerativo;

public class Edificio {
    private int idMapa;
    private int idEdificio;
    private int direccion;
    private Double [] localizacion;
    private Double ancho;
    private Double largo;
    private int tipoEdificio;
    private boolean banderaCirculacion;
    
    public Edificio(){
        
    }
    public Edificio(int idMapa, int idEdificio, int direccion , Double [] localizacion, Double ancho, Double largo, int tipoEdificio){
        this.idMapa=idMapa;
        this.idEdificio=idEdificio;
        this.direccion=direccion;
        this.localizacion=localizacion;
        this.ancho=ancho;
        this.largo=largo;
        this.tipoEdificio=tipoEdificio;
        banderaCirculacion=true;
    }
    public int getIdMapa() {
        return idMapa;
    }
    public void setIdMapa(int idMapa) {
        this.idMapa = idMapa;
    }
    public int getIdEdificio() {
        return idEdificio;
    }
    public void setIdEdificio(int idEdificio) {
        this.idEdificio = idEdificio;
    }
    public int getDireccion() {
        return direccion;
    }
    public void setDireccion(int direccion) {
        this.direccion = direccion;
    }
    public Double[] getLocalizacion() {
        return localizacion;
    }
    public void setLocalizacion(Double[] localizacion) {
        this.localizacion = localizacion;
    }
    public Double getAncho() {
        return ancho;
    }
    public void setAncho(Double ancho) {
        this.ancho = ancho;
    }
    public Double getLargo() {
        return largo;
    }
    public void setLargo(Double largo) {
        this.largo = largo;
    }
    public int getTipoEdificio() {
        return tipoEdificio;
    }
    public void setTipoEdificio(int tipoEdificio) {
        this.tipoEdificio = tipoEdificio;
    }
    public Boolean getBanderaCirculacion() {
        return banderaCirculacion;
    }
    public void setBanderaCirculacion(boolean ban) {
        this.banderaCirculacion = ban;
    }
    public Double calculaSuperficie(){
        return largo*ancho;
    }
    
    
}
