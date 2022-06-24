# Meus-Projetospackage br.com.iromedes.iron;

import java.awt.BorderLayout;

import javax.swing.JButton;
import javax.swing.JFrame;
import javax.swing.JPanel;

public class Programa4 {
	
    public static void main (String[] args) {
    	JFrame frame = new JFrame ("Iromedes");
    		
        JPanel panel = new JPanel();
        
        JButton btn1 = new JButton("Seja bem-vindo(a)");
        JButton btn2 = new JButton("Programação para leigos");
        JButton btn3 = new JButton ("Introdução a linguagem Java");
        
        panel.setLayout(new BorderLayout(1,0)); 
        
        panel.add(btn1, BorderLayout.NORTH);
        panel.add(btn2, BorderLayout.CENTER);
        panel.add(btn3, BorderLayout.SOUTH);
        
        frame.setContentPane(panel);
        frame.pack();
        frame.setSize(640, 480);
        frame.setVisible(true);
        			
    }
    
}
