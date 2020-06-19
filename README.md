package copa_piston;
import java.awt.*;
import javax.swing.*;
import java.util.concurrent.Semaphore;

public class Copa_Piston extends JFrame{
 PanelFondo p=new PanelFondo("pista.jpg");

 JLabel auto1;
 Icon imagen_auto1;

 JLabel tablero;
 Semaphore sh1, sh2, sh3, sh4, sh5;

 JLabel lblmin, lblseg, lblhor, a,b;
 JPanel cont;
 JLabel titulo,meta;
 Cronometro c=new Cronometro();
