# htmlcss-wp

Provato css Float con relativo clearFix
  nb:
    ::after{
    content:'';
    display:table;
    clear:both;
    
    
Provate anche 2 tecniche di overlay
  una con crazione div annidato
  una con pseudo selettore ::after
    display: block;
    content: '';
    height: 100%;
    /* width: 100%; */
    border-radius: 10px;
    background-color: rgba(0, 0, 0, 0.2);
