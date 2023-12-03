Per installare NeoVim ti basta clonare questa repo nei seguenti percorsi a partire dalla tilde:

Step 1

###Windows nella PowerShell:

    cd AppData/Local
    git clone git@github.com:PaoloTozzi/nvim.git

###Unix(Mac|Linux)

    cd .config
    git clone git@github.com:PaoloTozzi/nvim.git

- fai partire il comando nvim . 
- andare in lua/paoletoz/packer
- lanciare dalla visual mode i seguenti comandi:
    - :so || :source per eseguire il file packer che gestisce i nostri plugin
    - :PackerSync ("darà un warning ma non ci saranno problemi")

Ora il tuo setup è pronto:

- Puoi ovviamente personalizzare i tuoi plugin e aggiungerne altri


Ti invito per la personalizzazione a vedere questi link:

Packer (mason già installato)

- https://github.com/wbthomason/packer.nvim
- https://github.com/neovim/nvim-lspconfig/blob/master/doc/server_configurations.md LSP(language server Protocol) disponibili 


Per i comandi eseguibili in Nvim questo link:

- https://neovim.io/doc/user/vimindex.html

I comandi* per muoverti nei file sono
    
- Spazio|p|v oppure :Ex //per tornare a vedere il percorso dei file
- Spazio|p|f //per navigare tra i file
- :lua Color() //per fare in modo che lo sfondo diventi trasparente

Per gli altri comandi vedere il file keymaps.lua 

Per i comandi del lsp guardare il file lsp.lua


Ora che hai tutto pronto puoi personalizzarlo come preferisci in quanto Neovim non sarà il tuo IDE (Integrated Development Environment), ma sarà il tuo PDE (Personal Development Environment) :)


