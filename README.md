# Datu-kopas-tulkosana

Latvijas Universitātes Datorikas fakultātes bakalaura darba "APMĀCĪBAS DATU KOPAS TULKOŠANAS IETEKME UZ LIELO VALODAS MODEĻU SATURA REGULĒŠANU" ietvaros izstrādātais pirmkods mašīnmācīšanās modeļu apmācībai un novērtēšanai.

Satur divas datnes:
  - SQuAD.ipynb - Satur pirmkodu modeļu apmācībai un novērtēšanai, izmantojot SQuAD datu kopas
  - Instruct.ipynb - Satur pirmkodu modeļu apmācībai un novērtēšanai, izmantojot instrukciju bāzētu modeļa pielāgošanas procesu.
  - Instruct_train.json - Satur apmācības datus Instruct.ipynb pirmkodam
  - Instruct_validate.json - Satur validācijas datus Instruct.ipynb pirmkodam

Abu datņu sākumā ir pieejami "karodziņi", kuru izskaidrojums ir redzams komentāros. Ja pirmkodu ir nepieciešams testēt, ieteicams izmainīt šo "karodziņu" vērtības atbilstoši paredzētajai testa videi vai funkcionalitātei.

Pirmkoda testēšanas ietvaros tiek izmantota "Google Colab" lietotne.

SQuAD datu kopu ieguvei testešanas nolūkiem lūgums izmantot https://github.com/tilde-nlp/SQuAD-LV un https://rajpurkar.github.io/SQuAD-explorer/ kā oficiālās datu kopas latviešu un angļu valodās.
