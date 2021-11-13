# CoroutinesRetrofitMVVM2021
## MVVM
Aqui usamos a arquitetura MVVM

<img width="908" alt="Screen Shot 2021-11-12 at 21 14 13" src="https://user-images.githubusercontent.com/5742609/141597565-fb276346-346a-4a08-a731-bbf9f0db890f.png">

## [View Model](https://developer.android.com/topic/libraries/architecture/viewmodel?gclid=CjwKCAiAvriMBhAuEiwA8Cs5lY-JDt6C1uh2Nr4r-1Q65tvKIkZJv8EA7kVkIyE0_UokpQYpw89IchoC4uoQAvD_BwE&gclsrc=aw.ds)
A classe ViewModel foi projetada para armazenar e gerenciar dados relacionados à IU considerando o ciclo de vida. A classe ViewModel permite que os dados sobrevivam às mudanças de configuração, como a rotação da tela.

## [LiveData](https://developer.android.com/topic/libraries/architecture/livedata?hl=pt-br)
LiveData é uma classe armazenadora de dados observável. Diferente de um observável comum, o LiveData conta com reconhecimento de ciclo de vida, ou seja, ele respeita o ciclo de vida de outros componentes do app, como atividades, fragmentos ou serviços. Esse reconhecimento garante que o LiveData atualize apenas os observadores de componente do app que estão em um estado ativo no ciclo de vida.

## [Corrotinas do Kotlin no Android](https://developer.android.com/kotlin/coroutines?gclid=CjwKCAiAvriMBhAuEiwA8Cs5lQzJ-3Eiv2px-E23Iq12uadkReNe2n_N2OGrnHSjp8wU1sJT4oDzpRoCb_sQAvD_BwE&gclsrc=aw.ds)
Uma corrotina é um padrão de projeto de simultaneidade que você pode usar no Android para simplificar o código que é executado de forma assíncrona. Corrotinas foram adicionadas ao Kotlin na versão 1.3 e são baseadas em conceitos estabelecidos de outras linguagens (link em inglês).
No Android, as corrotinas ajudam a gerenciar tarefas de longa duração que podem bloquear a linha de execução principal e fazer com que seu app pare de responder. Mais de 50% dos desenvolvedores profissionais que usam corrotinas notaram um aumento na produtividade. Este tópico descreve como você pode usar corrotinas do Kotlin para resolver esses problemas, permitindo criar um código de app mais simples e conciso.

