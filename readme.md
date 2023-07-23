Diretivas:
==============

V-bind: ou ":" → → binding para com atributos de tags HTML
-----------------------------------------------------------
V-on: ou "@" → → binding para manipulação de eventos
               ↓
               ↓
               ↳ click → →
               ↳ keyup → → →
               ↳ mousemove → → →  Cada tipo de eventos possui modificadores próprios. 
               ↳ submit → → →     Os modificadores podem ser encadeados.                        
               ↳ scroll → →                 ↓               
                                            ↓  
                                            ↳ @click.prevent
                                            ↳ @click.once
                                            ↳ @click.prevent.once
                                            ↳ @keyup.a
                                            ↳ @keyup.shift.enter
-----------------------------------------------------
V-if → → Redenrização condicional de elementos HTML
                ↓ 
                ↓
                ↳ V-else
                ↳ V-else-if  
-----------------------------------------------------
v-show  → →  Exibição condicional de elementos (display)
---------------------------------------------------------
v-html  → →  Injeção de contúdo HTML (innerHTML)
-------------------------------------------------
v-text → → Injeção de Textos (innerText)
-----------------------------------------
v-once → → Faz com que elementos HTML seja redenrizados apenas uma única vez
-----------------------------------------------------------------------------



