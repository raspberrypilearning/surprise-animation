## Chwilfrydedd

<div style="display: flex; flex-wrap: wrap">
<div style="flex-basis: 200px; flex-grow: 1; margin-right: 15px;">
Fydd y gwrthrych yn gwneud rhywbeth i ddenu sylw? Sut bydd y cymeriad yn ymateb?

Ti sy'n penderfynu!
</div>
<div>

![Y prosiect 'BW!' yn dangos y cymeriad yn bod yn chwilfrydig.](images/boo.png)

</div>
</div>

### Y gwrthrych

--- task ---

**Dewis:** Os wyt ti am i'r gwrthrych wneud rhywbeth, dewisa beth bydd y gwrthrych yn ei wneud.

Ychwanega flociau i ddiwedd sgript gosod `pan fydd y faner werdd wedi'i chlicio`{:class="block3events"} y **gwrthrych**.

[[[scratch3-jiggle-a-sprite]]]

[[[scratch3-graphic-effects]]]

--- /task ---

### Y cymeriad

--- task ---

Mae angen cael y prif gymeriad i ddangos diddordeb yn y gwrthrych. Ychwanega flociau at ddiwedd sgript gosod y **cymeriad**.

Os oes angen i'r cymeriad aros nes bod y gwrthrych wedi gwneud rhywbeth, ychwanega floc `aros`{:class="block3control"}.

Fe allet ti ddefnyddio blociau `dweud`{:class="block3looks"} neu `meddwl`{:class="block3looks"}, neu hyd yn oed defnyddio'r estyniad `Testun i Leferydd`{:class="block3extensions"} i wneud i'r cymeriad siarad yn uchel!

[[[scratch3-text-to-speech]]]

Gallai'r cymeriad ddefnyddio emoshlun, fel yn prosiect [Sgwrs yn y Sêr](https://projects.raspberrypi.org/cy-GB/projects/space-talk){:target="_blank"}.

[[[scratch3-change-costumes-to-show-mood]]]

Gallai'r cymeriad fod yn ddewr a symud yn agosach i edrych ar y gwrthrych.

[[[scratch3-animate-movement-costumes]]]

--- /task ---

--- task ---

**Prawf:** Clicia ar y faner werdd i brofi dy brosiect. Dylai'r cymeriad ddangos chwilfrydedd tuag at y gwrthrych.

Clicia ar y faner werdd eto. Os wyt ti wedi newid safloedd neu edrychiad corluniau'r **gwrthrych** neu'r **cymeriad** bydd angen i ti wneud yn siŵr eu bod yn cael eu gosod yn ôl i'w safle neu eu hedrychiad cychwynol pan fyddi di'n rhedeg y prosiect eto.

--- collapse ---
---
teitl: Gosod y safle a'r edrychiad cychwynnol ar gyfer corlun
---

Dewisa'r blociau sydd eu hangen arnat i osod y safle ac edrychiad ar gyfer corlun ar y dechrau.

```blocks3
when flag clicked // ychwanegu blociau i osod y cychwyn 
switch costume to [costume1 v]
set size to (100) % // maint dechreuol
go to x: (-200) y: (50) // safle dechreuol
point in direction [90]
set [brightness v] effect to [80]
show
```

**Awgrym:** Mae'r holl effeithiau graffeg yn cael eu clirio pan fyddi di'n clicio ar y faner werdd, felly does dim angen i ti eu clirio, ond efallai y bydd angen i ti osod yr effeithiau rwyt ti am i'r corlun eu cael.

--- /collapse ---

--- /task ---

--- task ---

**Difa chwilod:**

--- collapse ---
---
title: Dydy'r sain ddim yn gweithio
---

Gwna'n siŵr bod lefel y sain ar dy gyfrifiadur neu dabled yn ddigon uchel a bod dy seinyddion neu glustffonau wedi'u cysylltu ac yn gweithio'n iawn.

--- /collapse ---

--- collapse ---
---
title: Dydy fy animeiddiad ddim yn ailosod yn iawn pan fyddaf yn clicio ar y faner werdd
---

Gwna'n siŵr bod gan dy brosiect sgriptiau `pan fydd y fflag werdd wedi'i chlicio`{:class="block3events"} ar gyfer y corluniau sydd eu hangen, a gwna'n siŵr eu bod yn ailosod safle, maint ac edrychiad y corluniau. I gael help gyda hyn, gweler y dasg **Gosod y safle a'r edrychiad cychwynnol ar gyfer corlun** uchod.

--- /collapse ---

--- /task ---

--- save ---
