---
title: "Ivanov sat programiranja #2: Ezoteričan jezik Befunge"
date: 2022-02-28T22:00:00+02:00
categories: [Ivanov sat programiranja]
tags: [Befunge]
draft: false
---

Definicija riječi ezoteričan ([HJP](https://hjp.znanje.hr/index.php?show=search_by_id&id=fFtgXBA%3D)):
> 1.	koji je namijenjen zatvorenom krugu, koji je tajan, skrovit (o okultnim tajnama), opr. egzoteričan
> 2.	koji je suviše zatvoren po smislu, koji je teško razumljiv, nečitljiv (o tekstovima, poeziji i sl.)

## Ezoterični programski jezici

- nastaju iz šale, lude ideje te kao posljedica istraživanja dizajna ili mogućnosti
- postoji ih nekoliko tisuća, najpoznatiji je `Brainf**k`
- možete ih istražiti na wiki stranici [Esolang](https://esolangs.org/wiki/Language_list)

## Primjeri `Hello, World!` programa

### Brainf**k

```text
+[-[<<[+[--->]-[<<<]]]>>>-]>-.---.>..>.<<<<-.<+.>>>>>.>.<<.<-.
```

### Chef

```text
Hello World Cake with Chocolate sauce.

This prints hello world, while being tastier than Hello World Souffle. The main
chef makes a " world!" cake, which he puts in the baking dish. When he gets the
sous chef to make the "Hello" chocolate sauce, it gets put into the baking dish
and then the whole thing is printed when he refrigerates the sauce. When
actually cooking, I'm interpreting the chocolate sauce baking dish to be
separate from the cake one and Liquify to mean either melt or blend depending on
context.

Ingredients.
33 g chocolate chips
100 g butter
54 ml double cream
2 pinches baking powder
114 g sugar
111 ml beaten eggs
119 g flour
32 g cocoa powder
0 g cake mixture

Cooking time: 25 minutes.

Pre-heat oven to 180 degrees Celsius.

Method.
Put chocolate chips into the mixing bowl.
Put butter into the mixing bowl.
Put sugar into the mixing bowl.
Put beaten eggs into the mixing bowl.
Put flour into the mixing bowl.
Put baking powder into the mixing bowl.
Put cocoa  powder into the mixing bowl.
Stir the mixing bowl for 1 minute.
Combine double cream into the mixing bowl.
Stir the mixing bowl for 4 minutes.
Liquify the contents of the mixing bowl.
Pour contents of the mixing bowl into the baking dish.
bake the cake mixture.
Wait until baked.
Serve with chocolate sauce.

chocolate sauce.

Ingredients.
111 g sugar
108 ml hot water
108 ml heated double cream
101 g dark chocolate
72 g milk chocolate

Method.
Clean the mixing bowl.
Put sugar into the mixing bowl.
Put hot water into the mixing bowl.
Put heated double cream into the mixing bowl.
dissolve the sugar.
agitate the sugar until dissolved.
Liquify the dark chocolate.
Put dark chocolate into the mixing bowl.
Liquify the milk chocolate.
Put milk chocolate into the mixing bowl.
Liquify contents of the mixing bowl.
Pour contents of the mixing bowl into the baking dish.
Refrigerate for 1 hour.
```

### Chicken

```text
chicken chicken chicken chicken chicken chicken chicken chicken chicken chicken chicken chicken chicken chicken chicken chicken chicken chicken chicken chicken
chicken chicken chicken chicken chicken chicken chicken chicken chicken chicken chicken chicken chicken chicken chicken chicken chicken chicken chicken chicken
chicken chicken chicken chicken
chicken chicken chicken chicken chicken chicken chicken chicken chicken
chicken chicken chicken chicken chicken chicken chicken chicken chicken chicken chicken
chicken chicken chicken chicken chicken chicken chicken
chicken chicken chicken chicken chicken chicken chicken chicken chicken chicken
chicken chicken chicken chicken chicken chicken chicken chicken chicken chicken chicken chicken chicken chicken chicken chicken
chicken chicken chicken chicken chicken chicken chicken chicken chicken chicken chicken chicken chicken chicken chicken chicken
chicken chicken chicken chicken
chicken chicken chicken
chicken chicken chicken chicken chicken chicken chicken chicken chicken chicken
chicken chicken chicken chicken chicken chicken chicken chicken chicken chicken chicken chicken chicken chicken chicken chicken chicken
chicken chicken chicken
chicken chicken chicken chicken chicken chicken chicken chicken chicken chicken
chicken chicken chicken chicken chicken chicken chicken chicken chicken chicken
chicken chicken chicken chicken chicken chicken chicken chicken chicken chicken chicken chicken chicken
chicken chicken chicken chicken chicken chicken chicken chicken chicken chicken chicken
chicken chicken chicken chicken chicken chicken chicken chicken chicken chicken chicken chicken
chicken chicken chicken chicken chicken chicken

chicken chicken chicken
chicken chicken chicken chicken chicken chicken chicken chicken chicken chicken chicken chicken chicken chicken
chicken chicken chicken chicken
chicken chicken chicken chicken chicken chicken chicken chicken chicken chicken chicken chicken chicken chicken chicken chicken chicken chicken chicken chicken chicken
chicken chicken chicken chicken chicken chicken chicken chicken chicken chicken chicken chicken chicken
chicken chicken chicken chicken chicken chicken chicken chicken chicken chicken chicken chicken chicken chicken chicken chicken
chicken chicken chicken chicken chicken chicken chicken chicken chicken chicken
chicken chicken chicken chicken chicken chicken chicken chicken chicken chicken chicken chicken chicken chicken chicken
chicken chicken chicken chicken chicken chicken chicken chicken chicken chicken chicken chicken chicken
chicken chicken chicken chicken chicken chicken

chicken chicken chicken chicken
chicken chicken chicken chicken chicken chicken chicken chicken chicken chicken chicken chicken chicken chicken chicken chicken chicken chicken
chicken chicken
chicken chicken
chicken chicken chicken chicken chicken chicken chicken chicken chicken
chicken chicken chicken chicken chicken chicken chicken chicken chicken chicken chicken
chicken chicken chicken chicken chicken chicken

chicken chicken
chicken chicken chicken chicken chicken chicken chicken chicken chicken chicken chicken
chicken chicken chicken chicken chicken chicken chicken
chicken chicken chicken chicken chicken chicken chicken chicken chicken chicken chicken chicken
chicken chicken chicken chicken chicken chicken

chicken chicken chicken chicken chicken chicken chicken chicken chicken chicken chicken chicken
chicken chicken chicken
chicken chicken chicken chicken chicken chicken chicken chicken chicken chicken chicken chicken
chicken chicken chicken chicken chicken chicken chicken
chicken chicken chicken chicken chicken chicken chicken chicken chicken chicken chicken chicken
chicken chicken chicken chicken chicken chicken

chicken chicken chicken chicken chicken chicken chicken chicken chicken chicken
chicken chicken chicken chicken chicken chicken chicken chicken chicken chicken chicken chicken chicken chicken chicken chicken chicken chicken chicken chicken chicken chicken chicken chicken chicken chicken chicken chicken chicken chicken chicken chicken chicken chicken chicken chicken chicken chicken chicken
chicken chicken chicken
chicken chicken chicken chicken chicken chicken chicken chicken
chicken chicken chicken chicken chicken chicken chicken chicken chicken chicken chicken
chicken chicken chicken chicken chicken chicken
```

### COW

```text
 MoO MoO MoO MoO MoO MoO MoO MoO MOO moO MoO MoO MoO MoO MoO moO MoO MoO MoO MoO moO MoO MoO MoO MoO moO MoO MoO MoO MoO MoO MoO MoO
 MoO MoO moO MoO MoO MoO MoO mOo mOo mOo mOo mOo MOo moo moO moO moO moO Moo moO MOO mOo MoO moO MOo moo mOo MOo MOo MOo Moo MoO MoO 
 MoO MoO MoO MoO MoO Moo Moo MoO MoO MoO Moo MMM mOo mOo mOo MoO MoO MoO MoO Moo moO Moo MOO moO moO MOo mOo mOo MOo moo moO moO MoO 
 MoO MoO MoO MoO MoO MoO MoO Moo MMM MMM Moo MoO MoO MoO Moo MMM MOo MOo MOo Moo MOo MOo MOo MOo MOo MOo MOo MOo Moo mOo MoO Moo
```

### DNA#

```text
   AT
  T--A
 A----T
 T-----A
 T-----A
 G----C
  T--A
   GC
   CG
  C--G
 A----T
 A-----T
 T-----A
 A----T
  A--T
   GC
   AT
  C--G
 T----A
 C-----G
 T-----A
 G----C
  C--G
   CG
   AT
  A--T
 T----A
 A-----T
 A-----T
 G----C
  A--T
   GC
   TA
  G--C
 T----A
 G-----C
 C-----G
 C----G
  A--T
   GC
   TA
  G--C
 A----T
 G-----C
 A-----T
 C----G
  A--T
   CG
   GC
  A--T
 A----T
 C-----G
 A-----T
 C----G
  A--T
   CG
   GC
  A--T
 T----A
 G-----C
 A-----T
 G----C
  A--T
   CG
   GC
  A--T
 G----C
 A-----T
 A-----T
 T----A
  A--T
   TA
   AT
  T--A
 G----C
 A-----T
 A-----T
 A----T
  G--C
   AT
   AT
  G--C
 T----A
 G-----C
 A-----T
 G----C
  G--C
   AT
   TA
  T--A
 A----T
 G-----C
 G-----C
 A----T
  A--T
   TA
   AT
  T--A
 A----T
 T-----A
 G-----C
 A----T
  T--A
   TA
   AT
  G--C
 A----T
 T-----A
 A-----T
 T----A
  G--C
   AT
   TA
  T--A
 A----T
 G-----C
 G-----C
 A----T
  A--T
   AT
   AT
  T--A
 G----C
 A-----T
```

### Drive-In Window

```text
Hi, welcome to Hello_World_Buffet. Here is a menu.

Rice Krispie Treat: $10
Ice Cream: $30
Cookies: $70

Here are your sides.

Whipped Cream: $1
Chocolate: $2
Caramel: $3

May I take your order?

Person 1 would like the Cookies with Chocolate.
Person 1 will pay for his order!
Person 2 would like the Ice Cream, hold the Whipped Cream.
Person 2 would also like what Person 1 has.
Person 2 will pay for his order!
Person 2 needs 7 dollars more for his order!
Person 2 will pay for his order!
Person 2 will pay for his order!
Person 2 needs 3 dollars more for his order!
Person 2 will pay for his order!
Person 3 would like the Ice Cream with Chocolate.
Person 3 will pay for his order!
Person 1 would also like the Rice Krispie Treat with Caramel.
Person 1 needs 2 more dollars for his order!
Person 1 will pay for his order!
Person 2 will pay for his order!
Person 2 needs 3 dollars more for his order!
Person 2 will pay for his order!
Person 2 needs 6 dollars less for his order!
Person 2 will pay for his order!
Person 2 needs 8 dollars less for his order!
Person 2 will pay for his order!
Person 3 needs 1 dollar more for his order!
Person 3 will pay for his order!
Just wait while we decide...

OK, that will be $1.14. Thanks for coming!
```

### Mycelium

[Hello, World!](https://esolangs.org/wiki/Hello_world_program_in_esoteric_languages_(nonalphabetic_and_A-M)#Mycelium)

### Pi

```text
  3.1415926535897932384226433232725028841271693992751358239749245923072164062
  822089986780348053431120629821483865332223366470908446395535832317223594083
  284831172502841037019385311052596446029489529303219642288009756259134461214
  751482337817834652812009021456285664234613486134553226482133236073603491413
  737242870066363155841744815239239622292545917053643278925902605113301301488
  204625213821429519415316024320522703627595939530921261373219226137931021185
  580744023794627495273518257527348912274384830113491298346743644406563430865
  2133494633522473749030217386093370277033921317659317670238267581846066440
```

### Pixiedust

```text
+           +               .   *+       ..  +.        ..            .                  .              .          
.
+            +   .*    +   +.    .    +           .+                         *
                   ++.        *   +  +  .  ++     .  .    *                         .              .      .   .       
.*
               +     +.     *  +    + .+         + .   .*                         .                 .   .    . ..
            ++      .  *     ++.    + ++        +  *                 .      .   ..          .              .*
           +     +   .* + .   +     +.              .  .                  .           .   .   .                .
              +           +  .*+           .   .. .     .*                                 .  .  . ..         . .   
.*
+               +.  *      +. +      .        ++          +*
 +         +. *+                       +       .  ++  ++             ..                                 .     ..
            +  +.        * +  +                 + ..   +  .*                         .
          + +        . *            ++        . + +       ..*            .                          ..
+                  +  .  *  ++.                  .+.. .          .    .                    . ...        ..
            +       +   .  *+                ..    . .    +*.         .      .       .         .       .*
```

### Poetic

```text
the proverbial "unconsciousness"

i was already aware
i had understood fully

i saw the devil
i was perfectly still
involuntarily i paused

there said i:
my sheer consciousness
of certain given circumstances
i noticed
it's nothing
     nothing
     nothing any man wouldn't learn

a way of finding these
i know not

nothing common or typical
and yet (somehow)
very little thought
will normally resolve every contradiction

a foolish heart -> an eternal misfortune
```

### Pokébattle

```text
Trainer 1: Alice
 Togepi
 Emolga
 Talonflame
 Rhyperior
 Abra
 Pikachu
Trainer 2: Bob
 Yveltal
 Raichu
 Oranguru
 Nidoqueen
 Incineroar
 Avalugg 
‌
Battle Start!
Turn 0:
 Alice: Rhyperior Go!
 Bob: Avalugg Go!

Turn 1:
 Rhyperior uses Absorb!
 Avalugg uses Absorb!

Turn 2:
 Rhyperior uses Absorb!
 Avalugg uses Absorb!

Turn 3:
 Alice: That's enough! Go Pikachu!
 Avalugg uses Splash!

Turn 4:
 Pikachu uses Absorb!
 Bob: That's enough! Go Raichu!

Turn 5:
 Alice: That's enough! Go Rhyperior!
 Raichu uses Absorb!

Turn 6:
 Rhyperior uses Splash!
 Bob: That's enough! Go Avalugg!

Turn 7:
 Rhyperior uses Absorb!
 Avalugg uses Absorb!

Turn 8:
 Alice uses Max Potion!
 Avalugg uses Tackle! It's not very effective.

Turn 9:
 Rhyperior uses Flamethrower!
 Avalugg uses Splash!

Turn 10:
 Rhyperior uses Swords Dance!
 Avalugg uses Swords Dance!

Turn 11:
 Rhyperior uses Tackle! It's not very effective.
 Bob uses Max Potion!

Turn 12:
 Rhyperior uses Skill Swap!
 Avalugg uses Swords Dance!

Turn 13:
 Rhyperior uses Swords Dance!
 Avalugg uses Tackle! It's not very effective.

Turn 14:
 Alice uses Hyper Potion!
 Bob: That's enough! Go Raichu!

Turn 15:
 Rhyperior uses Swords Dance!
 Bob uses Super Potion!

Turn 16:
 Alice: That's enough! Go Pikachu!
 Raichu uses Tackle! It's not very effective.

Turn 17:
 Pikachu uses Swords Dance!
 Raichu uses Swords Dance!

Turn 18:
 Alice: That's enough! Go Rhyperior!
 Bob uses Potion!

Turn 19:
 Alice uses Max Potion!
 Bob: That's enough! Go Avalugg!

Turn 20:
 Rhyperior uses Swords Dance!
 Avalugg uses Flamethrower! It's super effective!

Turn 21:
 Rhyperior uses Swords Dance!
 Avalugg uses Tackle! It's not very effective.

Turn 22:
 Alice uses Hyper Potion!
 Avalugg uses Splash!

Turn 23:
 Rhyperior uses Swords Dance!
 Avalugg uses Swords Dance!

Turn 24:
 Rhyperior uses Flamethrower! It's super effective!
 Avalugg uses Swords Dance!

Turn 25:
 Alice: That's enough! Go Abra!
 Bob: That's enough! Go Raichu!

Turn 26:
 Abra uses Splash!
 Raichu uses Swords Dance!

Battle End!
Winner: Alice
```

### Unicat

```text
😻😹😸🙀🙀😹😹😸🙀🙀😽😼😸🙀🙀😻😹😸🙀🙀😹😼😽🙀🙀😽😼😸🙀🙀😻😹😸🙀🙀😹😽😼🙀🙀😽😼😸🙀🙀😻😹😸🙀🙀😹😽😼🙀🙀😽😼😸🙀🙀😻😹😸🙀🙀😹😽😿🙀🙀😽😼😸🙀🙀😻😹😸🙀🙀😽😼🙀🙀😽😼😸🙀🙀😻😹😸🙀🙀😼😸🙀🙀😽😼😸🙀🙀😻😹😸🙀🙀😹😺😿🙀🙀😽😼😸🙀🙀😻😹😸🙀🙀😹😽😿🙀🙀😽😼😸🙀🙀😻😹😸🙀🙀😹😾😺🙀🙀😽😼😸🙀🙀😻😹😸🙀🙀😹😽😼🙀🙀😽😼😸🙀🙀😻😹😸🙀🙀😹😼😼🙀🙀😽😼😸🙀🙀😻😹😸🙀🙀😼😹🙀🙀😽😼😸🙀🙀😻😹😸🙀🙀😹😺🙀🙀😽😼😸🙀🙀🙀🙀
```

### Velato

[Hello, World!](https://esolangs.org/wiki/Hello_world_program_in_esoteric_languages_(N-Z)#Velato)

## Befunge

- jedan od poznatijih ezojezika
- 2D jezik, stogovno orijentiran
- program je torus veličine 80x25 znakova
- svaki je od znakova naredba ili podatak
- izvršavanje naredbi moguće je u svim smjerovima
- praznina je naredba koja ne radi ništa
- na stog se pohranjuju cijeli brojevi (C-ov `signed long int`)
- prazan stog vraća 0 kao vrijednost
- jezik je dostupan u dvama dijalektima: `Befunge-93` i `Befunge-98`
- nadahnuo je razne druge ezojezike pa i videoigru [Monster Logic](https://store.steampowered.com/app/917900/Monster_Logic/), koja je bila nadahnuće za ovo predstavljanje

### Naredbe

Preuzeto sa stranice https://catseye.tc/view/Befunge-93/doc/Befunge-93.markdown.

```text
COMMAND         INITIAL STACK (bot->top)RESULT (STACK)
-------         -------------           -----------------
+ (add)         <value1> <value2>       <value1 + value2>
- (subtract)    <value1> <value2>       <value1 - value2>
* (multiply)    <value1> <value2>       <value1 * value2>
/ (divide)      <value1> <value2>       <value1 / value2> (nb. integer)
% (modulo)      <value1> <value2>       <value1 mod value2>
! (not)         <value>                 <0 if value non-zero, 1 otherwise>
` (greater)     <value1> <value2>       <1 if value1 > value2, 0 otherwise>
> (right)                               PC -> right
< (left)                                PC -> left
^ (up)                                  PC -> up
v (down)                                PC -> down
? (random)                              PC -> right? left? up? down? ???
_ (horizontal if) <boolean value>       PC->left if <value>, else PC->right
| (vertical if)   <boolean value>       PC->up if <value>, else PC->down
" (stringmode)                          Toggles 'stringmode'
: (dup)         <value>                 <value> <value>
\ (swap)        <value1> <value2>       <value2> <value1>
$ (pop)         <value>                 pops <value> but does nothing
. (output int)  <value>                 outputs <value> as integer
, (output char) <value>                 outputs <value> as ASCII
# (bridge)                              'jumps' PC one farther; skips
                                        over next command
g (get)         <x> <y>                 <value at (x,y)>
p (put)         <value> <x> <y>         puts <value> at (x,y)
& (input int)                           <value user entered>
~ (input character)                     <character user entered>
@ (end)                                 ends program
```

### Programi

Mogu se isprobati na stranici https://angussbj.github.io/befunge/.

#### Hello, World!

```text
"!dlroW ,olleH">:v 
               ^,_@
```

#### Zbrajanje zadanih brojeva

```text
&&+.@
```

#### Fibonaccijev niz brojeva

```text
10v \+g10:p<
  >:.55+,01^
```

#### Bacanje zadanog broja kocaka

```text
&     v      
>5>5+,v,+5<5<
  5   :   5  
      !      
  .  @_1v .  
  1   v-< 5  
 >^   v  >^  
 ^?v# ? #^?v 
  v<      v< 
  6   #   2  
  .   >v  .  
^ <.3<?>4.> ^
     ^< 
```