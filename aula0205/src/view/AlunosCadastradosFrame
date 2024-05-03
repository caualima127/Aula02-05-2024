package view;

import javax.swing.*;

public class AlunosCadastradosFrame extends JFrame {
    private JMenuItem cadastrarMenuItem;
    private JMenuItem editarMenuItem;
    private JList<String> alunosList;
    private Controlador controlador;

    public AlunosCadastradosFrame() {
        initComponents();
    }
    private void initComponents() {
        cadastrarMenuItem = new JMenuItem("Cadastrar");
        cadastrarMenuItem.addActionListener(this::cadastrarMenuItemActionPerformed);
        
        editarMenuItem = new JMenuItem("Editar");
        editarMenuItem.addActionListener(this::editarMenuItemActionPerformed);
        
        JMenu menu = new JMenu("Opções");
        menu.add(cadastrarMenuItem);
        menu.add(editarMenuItem);
        
        JMenuBar menuBar = new JMenuBar();
        menuBar.add(menu);
        
        setJMenuBar(menuBar);
    }
    public void setControlador(Controlador controlador) {
        this.controlador = controlador;
    }
    private void cadastrarMenuItemActionPerformed() {    
    }
    private void editarMenuItemActionPerformed() {   
    }
    private void carregarDados() {   
    }
    public void atualizarDados() {     
    }
}
