# CoroutinesRetrofitMVVM2021
## MVVM
Aqui usamos a arquitetura MVVM

<img width="908" alt="Screen Shot 2021-11-12 at 21 14 13" src="https://user-images.githubusercontent.com/5742609/141597565-fb276346-346a-4a08-a731-bbf9f0db890f.png">

## [View Model](https://developer.android.com/topic/libraries/architecture/viewmodel?gclid=CjwKCAiAvriMBhAuEiwA8Cs5lY-JDt6C1uh2Nr4r-1Q65tvKIkZJv8EA7kVkIyE0_UokpQYpw89IchoC4uoQAvD_BwE&gclsrc=aw.ds)
A classe ViewModel foi projetada para armazenar e gerenciar dados relacionados à IU considerando o ciclo de vida. A classe ViewModel permite que os dados sobrevivam às mudanças de configuração, como a rotação da tela.


## Corrotinas do Kotlin no Android
Uma corrotina é um padrão de projeto de simultaneidade que você pode usar no Android para simplificar o código que é executado de forma assíncrona. Corrotinas foram adicionadas ao Kotlin na versão 1.3 e são baseadas em conceitos estabelecidos de outras linguagens (link em inglês).

No Android, as corrotinas ajudam a gerenciar tarefas de longa duração que podem bloquear a linha de execução principal e fazer com que seu app pare de responder. Mais de 50% dos desenvolvedores profissionais que usam corrotinas notaram um aumento na produtividade. Este tópico descreve como você pode usar corrotinas do Kotlin para resolver esses problemas, permitindo criar um código de app mais simples e conciso.
Há três entidades envolvidas em streams de dados:

### Recursos

As corrotinas são nossa solução recomendada para programação assíncrona no Android. Os recursos notáveis incluem o seguinte:

* Leve: é possível executar muitas corrotinas em uma única linha de execução devido à compatibilidade com a suspensão (link em inglês), que não bloqueia a linha de execução em que a corrotina está sendo executada. A suspensão economiza memória em vez de bloquear, oferecendo compatibilidade com muitas operações simultâneas.
* Menos vazamentos de memória: use simultaneidade estruturada (link em inglês) para executar operações em um escopo.
* Suporte de cancelamento integrado: o cancelamento (link em inglês) é propagado automaticamente por meio da hierarquia da corrotina em execução.
* Integração com o Jetpack: muitas bibliotecas do Jetpack incluem extensões que oferecem compatibilidade total com corrotinas. Algumas bibliotecas também fornecem o próprio escopo de corrotina que pode ser usado para simultaneidade estruturada.

Exemplo de código usando coroutines:

