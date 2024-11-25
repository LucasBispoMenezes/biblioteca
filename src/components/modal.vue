<template>
  <div class="modal" tabindex="-1" id="CreateBook">
    <div class="modal-dialog">
      <div class="modal-content">
        <div class="modal-header">
          <h5 class="modal-title">Adicionar Livro</h5>
          <button type="button" class="btn-close" data-bs-dismiss="modal" aria-label="Close"></button>
        </div>
        <div class="modal-body">
          <form>
            <div class="mb-3">
              <label for="title" class="form-label">Título</label>
              <input type="text" class="form-control" id="title" placeholder="Digite o título do livro" required>
            </div>
            <div class="mb-3">
              <label for="author" class="form-label">Autor</label>
              <input type="text" class="form-control" id="author" placeholder="Digite o nome do autor" required>
            </div>
            <div class="mb-3">
              <label for="year" class="form-label">Ano de Publicação</label>
              <input type="number" class="form-control" id="year" placeholder="Digite o ano de publicação" required>
            </div>
            <div class="mb-3">
              <label for="url_image">Link da imagem</label>
              <input type="text" class="form-control" id="url_image" placeholder="Digite a url da imagem do livro"
                required>
            </div>
          </form>
        </div>
        <div class="modal-footer">
          <button type="button" class="btn btn-secondary" data-bs-dismiss="modal">fechar</button>
          <button type="button" class="btn btn-primary">salvar</button>
        </div>
      </div>
    </div>
  </div>
</template>