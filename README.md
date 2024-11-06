<article class="cartao">
        <div class="cartao__conteudo">
                <h3>Programação</h3>
                <div class="cartao__conteudo__pergunta">
                        Qual o nome completo do jogador Kaká 
                </div>
                <div class="cartao__conteudo__resposta">
                        O nome completo dele é Ricardo izecson dos santos leite
                </div>
        </div>
</article>
<article class="cartao">
        <div class="cartao__conteudo">
                <h3>Programação</h3>
                <div class="cartao__conteudo__pergunta">
                        O que é CSS?
                </div>
                <div class="cartao__conteudo__resposta">
                        O CSS é uma linguagem de estilização
                </div>
        </div>
</article>
<!-- código omitido -->

<article class="cartao">
        <div class="cartao__conteudo">
            <h3>Programação</h3>
            <div class="cartao_conteudo_pergunta"> 
                <p>O que é CSS?</p>
            </div>
            <div class="cartao_conteudo_resposta">
            <p>0 CSS é uma linguagem de estilização</p>
        </div>
    </div>
</article>

<!-- código omitido -->
<section id="container">
        <!-- <article class="cartao">
                <div class="cartao__conteudo">
                        <h3>Programação</h3>
                        <div class="cartao__conteudo__pergunta">
                                <p>O que é JavaScript?</p>
                        </div>
                        <div class="cartao__conteudo__resposta">
                                <p>O JavaScript é uma linguagem de programação</p>
                        </div>
                </div>
        </article> -->
</section>
/* código omitido */

@media (max-width: 560 px) {

    body {
        background: url('img/bd-mobile.webp');
    }
    
    .cartao {
        flex: 1 0 calc(100% - 1rem);
    }
    
    .cartao__conteudo h3 {
        font-size: 3vw;
    }
    
    .cartao__conteudo p {
        font-size: 3.8vw;
    }
}
  
