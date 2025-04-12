# frontend
- brew install nvm   
- nano ~/.zshrc
- Then add these lines at the bottom (or make sure they’re there):
export NVM_DIR="$HOME/.nvm"
[ -s "$(brew --prefix nvm)/nvm.sh" ] && \. "$(brew --prefix nvm)/nvm.sh"
- mkdir -p ~/.nvm
- source ~/.zshrc
- nvm install v22
- nvm use v22       
- npm install
- npm run dev