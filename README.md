## Vuejs

- Template Syntax
  - vulnerabilità XSS, perchè usare v-html quindi?
  - l'interpolazione serve ad incollare stringhe con il {{mustache}}
  - tutto ciò che è preceduto da v- è una direttiva fornita da Vue
  - si sostituisce al mustache per quando c'è bisogno di scrivere dentro l'attributo HTML la direttiva v-bind es (v-bind:style="customVueProperty")
  - sintassi abbrevviata :style="customVueProperty"
  - puoi mettere più attributi insieme scrivendo v-bind="attributiCustom"
  - cos'è il controllo di flusso?
