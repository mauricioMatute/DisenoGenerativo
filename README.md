# DisenoGenerativo

package paqueteDiseñoGenerativo;

public class Terreno {
    private int idMapa;
    private double lado1Longitud;
    private boolean lado1Colindancia;
    private double lado2Longitud;
    private boolean lado2Colindancia;
    private boolean lado3Colindancia;
    private boolean lado4Colindancia;
    private double restriccionBorde;
    private int restriccionDePisos;
    
public Terreno(){

}

public Terreno(int idMapa, double lado1Longitud, boolean lado1Colindancia, double lado2Longitud, boolean lado2Colindancia, boolean lado3Colindancia, boolean lado4Colindancia, double restriccionBorde, int restriccionDePisos){
    this.idMapa = idMapa;
    this.lado1Longitud= lado1Longitud;
    this.lado1Colindancia = lado1Colindancia;
    this.lado2Longitud = lado2Longitud;
    this.lado2Colindancia = lado2Colindancia;
    this.lado3Colindancia = lado3Colindancia;
    this.lado4Colindancia = lado4Colindancia;
    this.restriccionBorde = restriccionBorde;
    this.restriccionDePisos = restriccionDePisos;
}

  
    public int getIdMapa() {
        return idMapa;
    }

   
    public void setIdMapa(int idMapa) {
        this.idMapa = idMapa;
    }

    public double getLado1Longitud() {
        return lado1Longitud;
    }

    public void setLado1Longitud(double lado1Longitud) {
        this.lado1Longitud = lado1Longitud;
    }

    public boolean isLado1Colindancia() {
        return lado1Colindancia;
    }

    public void setLado1Colindancia(boolean lado1Colindancia) {
        this.lado1Colindancia = lado1Colindancia;
    }

    public double getLado2Longitud() {
        return lado2Longitud;
    }

    public void setLado2Longitud(double lado2Longitud) {
        this.lado2Longitud = lado2Longitud;
    }

    public boolean isLado2Colindancia() {
        return lado2Colindancia;
    }

    public void setLado2Colindancia(boolean lado2Colindancia) {
        this.lado2Colindancia = lado2Colindancia;
    }

    public boolean isLado3Colindancia() {
        return lado3Colindancia;
    }

    public void setLado3Colindancia(boolean lado3Colindancia) {
        this.lado3Colindancia = lado3Colindancia;
    }

    public boolean isLado4Colindancia() {
        return lado4Colindancia;
    }

    public void setLado4Colindancia(boolean lado4Colindancia) {
        this.lado4Colindancia = lado4Colindancia;
    }

    public double getRestriccionBorde() {
        return restriccionBorde;
    }

    public void setRestriccionBorde(double restriccionBorde) {
        this.restriccionBorde = restriccionBorde;
    }

    public int getRestriccionDePisos() {
        return restriccionDePisos;
    }

    public void setRestriccionDePisos(int restriccionDePisos) {
        this.restriccionDePisos = restriccionDePisos;
    }
}

