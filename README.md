# Ransomware-filegroup

> Gera um arquvio XML responsável por popular a base de extesões ransomwares não permitidas no filegroup do Windows Server 2008 / 2008 r2. 
> Para versões posteriores use o script https://github.com/wanderleihuttel/protect-ransomware

## Requisistos:

  python 3
  
  pip install -r requirements.txt
  
# Instalação

    # Mudar Caminho padrão do diretorio windows na última linha
    # tree.write("C:\\TEMP\\rans.xml", short_empty_elements=False, xml_declaration=True, encoding='utf16')

    # Execute o comando e modifique <PATH> no windows 2k8 / 2k8r2 - 
    # "filescrn.exe f i /File:C:\<PATH>\rans.xml /Overwrite"
  
 
