# AGENTS

Instruções obrigatórias para qualquer agente que alterar este repositório:

1. **Toda alteração deve ser commitada e pushada.**
   - Após qualquer criação, edição ou remoção de arquivos, execute:
     `git add -A`, `git commit -m "<mensagem clara>"` e `git push`.
   - Nunca deixe alterações apenas locais ao final da tarefa.
2. Antes de commitar, confira `git status` e `git diff` para incluir
   apenas os arquivos pretendidos. Nunca commite segredos ou tokens.
3. O jogo é um arquivo único (`index.html`); valide a sintaxe do
   JavaScript (`node --check`) antes de commitar quando possível.
4. O deploy é via GitHub Pages (branch `main`, pasta `/root`).
   Não é preciso fazer nada extra para publicar: o push atualiza o site.
