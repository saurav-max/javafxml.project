import java.awt.Component;

import javax.swing.JButton;
import javax.swing.JFrame;
import javax.swing.JLabel;
import javax.swing.JPanel;
import javax.swing.JPasswordField;
import javax.swing.JTextField;

public class gui {

	public static void main(String[] args) {
		
		
		
		
		JPanel panel=new JPanel();
		JFrame frame=new JFrame();
		frame.setSize(100,100);
		frame.setDefaultCloseOperation(JFrame.EXIT_ON_CLOSE);
		
		frame.add(panel);
		
		panel.setLayout(null);
		JLabel userlabel=new JLabel("NAME");
		userlabel.setBounds(10,20,80,25);
		panel.add(userlabel);
		JTextField userText=new JTextField(20);
		userText.setBounds(100,20,165,25);
		panel.add(userText);
		
		JLabel passwordLabel=new JLabel("GRADUATION YEAR");
		passwordLabel.setBounds(10,50,80,25);
		panel.add(passwordLabel);
		
		JPasswordField passwordText=new JPasswordField();
		passwordText.setBounds(100,50,165,25);
		panel.add(passwordText);
		
		
		JButton button=new JButton("submit");
		button.setBounds(10,80,80,25);
		panel.add(button);
		
		JLabel success=new JLabel("");
		success.setBounds(10,30,40,70);
		panel.add(success);
		
		
		
		
		
		
		
		frame.setVisible(true);
		
		
		
	}

}![javafx](https://user-images.githubusercontent.com/54424730/143619265-4a9369ad-ea3d-4237-9f44-a0eb0975d356.png)
