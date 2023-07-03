# ML-Inadiplencia
Uma machine learn para concessão de empréstimos.

Caso deseje usar o backup do banco de dados seguir os passos a seguir:

1-Crie uma pasta e descompacte o arquivo backupcredito.tar

2-No Pgadmin crie um banco de dados qualquer

3-Exclua o schema public deste banco de dados, pelo próprio pgadmin

4-Clique com o botão direito no banco de dados e selecione restaurar. Se aparecer a mensagem Utility file not found. Please correct the Binary Path in the Preferences dialog, veja abaixo como resolver

5-Na janela de restore, selecione Directory para Format

6-Em Filename aponte para o diretório onde descompactou o arquivo

7-Number of jobs pode colocar 1

8-Clique em Restore

Utility file not found. Please correct the Binary Path in the Preferences dialog

Caso essa mensagem aparecer:

1-Localize o path da pasta bin do postgres no seu comptuador, vai ser algo como "C:\Program Files\PostgreSQL\15\bin"

2-Abra o pgAdmin e vá para o menu "File" e selecione "Preferences" (ou "Options" em algumas versões).

3-Na caixa de diálogo "Preferences", selecione a categoria "Paths".

4-Em PostgreSQL Binary Path, cole o caminho em Binary Path, e marque "Set as Default"
