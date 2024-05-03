package view;

import javax.swing.*;
import model.Aluno;

public class AlunoFrame extends JFrame {
    private JTextField nomeTextField;
    private JButton okButton;
    private JButton cancelarButton;
    private JTextField notaTextField;
    private Controlador controlador;
    private Aluno aluno;
    private boolean editando;

    public AlunoFrame() {
        initComponents();
    }

    private void initComponents() {
        nomeTextField = new JTextField();
        okButton = new JButton();
        cancelarButton = new JButton();
        notaTextField = new JTextField();

        setDefaultCloseOperation(javax.swing.WindowConstants.EXIT_ON_CLOSE);

        okButton.setText("OK");
        okButton.addActionListener(new java.awt.event.ActionListener() {
            public void actionPerformed(java.awt.event.ActionEvent evt) {
                okButtonActionPerformed(evt);
            }
        });

        cancelarButton.setText("Cancelar");
        cancelarButton.addActionListener(new java.awt.event.ActionListener() {
            public void actionPerformed(java.awt.event.ActionEvent evt) {
                cancelarButtonActionPerformed(evt);
            }
        });

    }
    public void setControlador(Controlador controlador) {
        this.controlador = controlador;
    }
    private void okButtonActionPerformed(java.awt.event.ActionEvent evt) {
    }
    private void cancelarButtonActionPerformed(java.awt.event.ActionEvent evt) {
    }
    private void thisWindowClosing(java.awt.event.WindowEvent evt) {
    }
    private void carregarDados() {
    }
}

