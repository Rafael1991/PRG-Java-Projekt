# PRG-Java-Projekt

// Nikitas Part01

package bildbearbeitung01;

import javax.swing.JButton;
import javax.swing.JFrame;
import javax.swing.JPanel;

public class window01 {

	public static void main(String[] args) {
		// TODO Auto-generated method stub
		
		// Window
		JFrame frame = new JFrame("Bildbearbeitungsprogramm");
		frame.setSize (450,300);
		frame.setDefaultCloseOperation(JFrame.EXIT_ON_CLOSE);
		JPanel panel = new JPanel();
		
		//Button
		JButton button0 = new JButton("Neue Seite");
		button0.setSize(300,10); // (geschätzte x,y Koordinaten, funktioniert nicht ?!)
		
		frame.add(panel);
		frame.setVisible(true);
		panel.add(button0);
	}

}


