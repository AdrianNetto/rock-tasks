# Out of Office Script 🏖️

Este é um script em JavaScript que facilita a criação de eventos "Out of Office" (OOO) utilizando a API do Rock. O script permite configurar um título, tempo de duração e descrição para o OOO, garantindo que você informe sua ausência de forma rápida e prática.

Lembre-se de instalar as dependencias com o comando `npm install`.

## 🛠️ Uso
Execute o script com o seguinte comando:

`node index.js <minutos> <descrição>`

`<minutos>`: Tempo (em minutos) até o fim do status OOO.

`<descrição>`: (Opcional) Texto descritivo para o OOO.

### Exemplo de uso

`node index.js 15 "Vou ao Ponto do Real"`

Se você não fornecer uma descrição, será usada a mensagem padrão:

"🥖 Vou à panificadora."


## Confirmação

O script exibe os detalhes do OOO antes de enviar à API e solicita sua confirmação. Para confirmar, digite:

`s` ou `sim` para criar o OOO.
Qualquer outra tecla para cancelar.