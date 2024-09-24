Uma extensão para Chrome Manifest V3 para escolher um dispositivo de saída de áudio preferido para os elementos HTML5 <audio/> e <video/>.

Como funciona
A extensão encontra elementos HTML5 <audio/> e <video/> na árvore do documento e manipula o sinkId para alternar para o dispositivo de saída de áudio preferido. Desde a versão 0.3.8, ela também encontra objetos Audio, Video e AudioContext que não foram inseridos na árvore do documento. Isso significa que plataformas como Spotify e SoundCloud também devem funcionar com a extensão.

Como agora é possível armazenar/lembrar um dispositivo de áudio preferido por site/domínio, o painel de opções da extensão e a opção de definir um dispositivo preferido global (para o navegador) foram removidos. Isso também reduz significativamente o número de permissões de microfone que a extensão solicita (veja abaixo).

Nota que a API Media Capture and Streams exige que permissões de mídia (microfone) sejam concedidas a cada site que precisa manipular saídas de áudio. Isso permite que esses sites acessem seu microfone. Por isso, o AudioPick só solicita permissões quando o usuário escolhe um dispositivo não padrão para um site e restaura as permissões quando o usuário volta a usar o dispositivo padrão. Desde a versão 0.3.10, um modo chamado smartMicAccess pode ser ativado na interface, o que reduz ainda mais o número de permissões de microfone concedidas pela extensão.

Consulte o FAQ e o ChangeLog para mais informações.

Código Aberto e Livre (Free/Libre Open Source)
Publicamos este software como Código Aberto e Livre (Free/Libre Open Source) sob a licença GPL-3.0, garantindo que você tenha e continue tendo as seguintes quatro liberdades fundamentais:

a liberdade de usar o software para qualquer finalidade,
a liberdade de modificar o software para atender às suas necessidades,
a liberdade de compartilhar o software com seus amigos e vizinhos, e
a liberdade de compartilhar as mudanças que você fizer.
– Os Fundamentos da GPL

Embora Código Aberto e Livre (Free/Libre Open Source) refira-se a livre como em liberdade de expressão, e não como em cerveja grátis, optamos por:

não cobrar pelos nossos softwares,
não re-licenciar nosso software sob uma licença comercial,
não oferecer benefícios ou recursos adicionais para usuários que paguem, e
não colocar anúncios comerciais em nosso software ou em nossas páginas da web.
No entanto, aceitamos ❤Gratificações.

Privacidade
Privacidade e Liberdade andam de mãos dadas. Você não deve ser forçado a divulgar dados pessoais para poder usar um software ou acessar informações importantes. Por isso, nem nosso software nem nossas páginas da web coletam dados de uso ou exigem registro.

Nossas páginas da web são documentos HTML estáticos e não configuram cookies. Elas não contêm nenhum código JavaScript, a menos que seja necessário para fornecer uma função específica, como busca local, ou demonstrar algum código em ação.

Nosso software, no caso a extensão AudioPick, não rastreia dados de uso por si só, embora você deva estar ciente de que instalar uma extensão da Chrome Web Store e usá-la no navegador Chrome gera dados de uso, que são mostrados na Chrome Web Store e no Developer Dashboard, como quantas vezes a extensão foi instalada. Optamos por não usar google-analytics para rastrear e avaliar os dados de uso. Além disso, note que baixar a extensão pelo GitHub provavelmente também deixa um rastro.

Se tivermos acesso a dados de uso/usuário, como IP ou endereços de e-mail, será algo inevitável, e fazemos o possível para eliminar informações desnecessárias, como rotacionar arquivos de log dos servidores que controlamos. De qualquer forma, não transferimos ou vendemos esses dados para terceiros.

Gratificações
Dito isso, você pode demonstrar apreço pelo nosso trabalho pagando uma gorjeta totalmente voluntária. Para esse fim, criamos um ❤Link de pagamento no Stripe, que permite você contribuir com qualquer valor entre 1€ e 10€, sendo o valor padrão 3€, para manter a taxa de processamento sob controle.

Infelizmente, usar esse link/página para gorjetas não é anônimo, pois o Stripe exige que você insira um endereço de e-mail válido, mas não encontramos uma forma melhor/mais privada de receber contribuições monetárias pela internet. Portanto, use o link/página apenas se estiver ciente e de acordo com as implicações de privacidade.

Links
Extensão AudioPick na Chrome Webstore
Código-fonte do AudioPick no GitHub
Problemas do AudioPick no GitHub
Página inicial do AudioPick
Página inicial Rain-Fighters
Contribuições
As versões do Manifest V3 (0.3.X) são originadas de uma reescrita completa (da nossa versão do Manifest V2), gentilmente contribuída por @XanSama e @joaoramosty 🎄 Obrigado! 🎄
