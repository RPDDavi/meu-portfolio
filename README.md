<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Estudo programação</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-QWTKZyjpPEjISv5WaRU9OFeRpok6YctnYmDr5pNlyT2bRjXh0JMhjY6hW+ALEwIH" crossorigin="anonymous">
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header class="container-fluid p-2 bg-warning text-center">
        <nav class="navbar navbar-expand-lg bg-warning">
            <div class="container-fluid">
              <a class="navbar-brand" href="#">RPDCODE</a>
              <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
                <span class="navbar-toggler-icon"></span>
              </button>
              <div class="collapse navbar-collapse justify-content-end" id="navbarNav">
                <ul class="navbar-nav">
                  <li class="nav-item">
                    <a class="nav-link active" aria-current="page" href="#">Aprenda a programação</a>
                  </li>
                  <li class="nav-item">
                    <a class="nav-link" href="#">HTML</a>
                  </li>
                  <li class="nav-item">
                    <a class="nav-link" href="#">CSS</a>
                  </li>
                  <li class="nav-item">
                    <a class="nav-link disabled" aria-disabled="true">PACOTES</a>
                  </li>
                </ul>
              </div>
            </div>
          </nav>
        <h1>Aprenda-Ja</h1>
    </header>
    
    <div class="curso">
        <img src="./img/download (2).jpeg" alt="Curso"><br><br><br><br>
    
    </div>
    <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Mauris sed risus vitae diam elementum eleifend. Vestibulum varius erat a mi semper, eget tincidunt lectus vulputate. Phasellus feugiat nibh turpis, eu scelerisque quam tempor nec. Duis sed ante lorem. Suspendisse molestie, diam ultrices commodo accumsan, purus purus vehicula augue, eu maximus diam velit et eros. Morbi dignissim nec lorem eu volutpat. Aliquam purus metus, dictum eu odio ac, imperdiet euismod tortor. Sed mauris felis, venenatis non aliquam id, laoreet sit amet ex. Curabitur vel pharetra libero.

        Proin tempus massa et felis sollicitudin facilisis. Quisque ornare, augue ut faucibus fermentum, est nisl pharetra arcu, non interdum metus massa tempus justo. Aliquam sit amet elementum turpis. Fusce ultricies neque et rhoncus blandit. Vestibulum auctor justo in turpis imperdiet, et pretium sem tincidunt. Duis hendrerit lacus in nunc venenatis, quis eleifend enim aliquet. Morbi lacinia dignissim ex. Pellentesque habitant morbi tristique senectus et netus et malesuada fames ac turpis egestas. Nam blandit mollis augue, at pretium ex volutpat tempor. Curabitur massa ligula, lobortis condimentum augue et, porta egestas nunc. Integer vitae tellus sit amet enim maximus vestibulum. Interdum et malesuada fames ac ante ipsum primis in faucibus.
        </p>
        <a href="https://www.w3.org/">Site oficial da W3C</a>
       <section class="container-fluid bg-light text-center">
        <h2>Como aprender?</h2>
            <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus molestie purus ut interdum rhoncus. Vestibulum lobortis eleifend eros eget pretium. Ut vel lobortis turpis. In hac habitasse platea dictumst. Sed finibus efficitur neque, eget pharetra ante malesuada sit amet. Vivamus tincidunt, magna quis sagittis aliquam, dui quam efficitur dui, vitae ullamcorper sapien ligula sit amet mi. Nullam vel tellus vitae neque pretium facilisis. Curabitur ornare dapibus tortor in viverra. In dapibus mauris sit amet aliquam dictum. Fusce pulvinar leo quis magna scelerisque mattis. Sed consectetur hendrerit leo ut hendrerit.</p>
            <div class = "row">
                <figure class="col text-center">
                    <img src="./img/html.png" alt="HTML">
                    <figcaption>HTML 123...</figcaption>
                   </figure>
                   <hr>
                   <figure class="col text-center">
                    <img src="./img/css.png" alt="css">
                    <figcaption>CSS 123...</figcaption>
                   </figure><br><br><br><br><br>
        
       <br><br><br><br><br><br>

        </section><br><br><br>    
        <section class="container-fluid bg-light">
            <legend> Contato</legend>

            <div class="mb-3">
                <label class="form-label" for="nome">Nome</label>
                <input type="text" class="form-control" name="Nome" id="nome"><br><br>
            </div>

            <form method="GET" action="">
                <fieldset>
                    <legend>Dados da Viagem</legend>
                    
                <div class="mb-3">
                    <label class="form-label" for="email">E-mail</label><br>
                <input type="email" class="form-control" name="Email" id="email">
                </div>

                <div class="mb-3">
                    <label class="form-label" for="DataIda">Data de ida</label><br>
                <input type="date" class="form-control" name="dataIda" id="DataIda">
                </div>
                
                <div class="mb-3">
                    <label class="form-label" for="DataVolta">Data de Volta</label><br>
                    <input type="date" class="form-control" name="dataVolta" id="DataVolta"><br><br>
                </div>

                <div class="mb-3">
                    <label class="form-label" for="QtdPessoas">Quantidades de Pessoas</label><br>
                <input type="number" class="form-control" name="qtdPessoas" id="QtdPessoas">
                </div>

                
                </fieldset><br><br>
                
                <section class="container-fluid bg-light">
                    <fieldset>
                        <legend>Quais Serviços deseja contratar?</legend><br>
                        <label>
                            <br><input type="checkbox" name="passagens" value="Passagens"> Compra de passagens
                        </label>
                        
                        <label>
                            <br><input type="checkbox" name="hospedagem" value="Hospedagem">Reserva de hospedagem
                        </label>
    
                        <label>
                            <br><input type="checkbox" name="vaiculos">Reserva de veiculos
                        </label>
                    </fieldset><br>
              
            
    
                    <fieldset>
                        <legend>Escolha a forma de pagamento</legend>
                        <label>
                            <br><input type="radio" name="formaPagamento" value="Cartão de crédito"> Cartão de crédito
                        </label>
                        <label>
                            <br><input type="radio" name="formaPagamento" value="Boleto"> Boleto
                        </label>
    
                        <label>
                            <br><input type="radio" name="formaPagamento" value="Pix"> Pix
                        </label>
                    </fieldset>
                    
                    <fieldset>
                        <legend>Escolha o prazo para pagamento</legend>
                        <select name="prazoPagamento">
                            <option value="avista">Á vista</option>
                            <option value="5x">5x sem juros</option>
                            <option value="10x">10x com juros</option>
                        </select>
                    </fieldset>
                    
                    
                    <label>Comentarios</label><br>
                    
                    <textarea rows="5" name="Comentarios"></textarea><br><br>
                    
                    <button>Enviar</button>               
                </section><br><br><br><br>
                
        <section class="container-fluid bg-light">
            <section>
                <h2>Taxas e Serviços</h2>
            </section>
            
            <p>Veja nossas taxas e serviços</p>
            <table>
                <caption>Descrição dos Serviços</caption>
                <thead>
                <tr>
                    <th>
                        Serviços
                    </th>
                    <th>
                        Valor
                    </th>
                </tr>
                </thead>
            <tbody>
                <tr>
                    <td>
                        Reservas
                    </td>
                    <td>
                        R$500,00
                    </td>
                </tr>
                <tr>
                    <td>
                        Compra de Modúlos
                    </td>
                    <td>
                        R$250,00
                    </td>
                </tr>
            </tbody>
            <tfoot>
                <tr>
                    <td>
                        Serviço
                    </td>
                    <td>
                        Valor
                    </td>
                </tr>
            </tfoot>
            </table>
        </section>
<footer class="container-fluid bg-warning">
    <p>Davi Ribeiro-07/02/2024</p
></footer>
<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js" integrity="sha384-YvpcrYf0tY3lHB60NNkmXc5s9fDVZLESaAA55NDzOxhy9GkcIdslK1eN7N6jIeHz" crossorigin="anonymous"></script>

</body>
</html>
