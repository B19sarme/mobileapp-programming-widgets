
# Rapport

**Skriv din rapport här!**
I den första frågan var det att göra tre olika ändringarna i appen och jag gjorde utifrån vad som jag har lärt mig hittlis och dem tre ändringarna var följande börja med att byta 
appnamnet på titlen, sedan så ändrad jag android texten som fanns på appen och sedan gav jag internet återkomst till appen för det var några saker som man har lärt sig innan. 
Samt så har en massa widgets och layouts ändrats och det har ändrats på margin och placeringarna så att det ser snyggare ut på appen, några saker som har lagts,
är att Button, Editview och Imageview för göra appen desto proffsigare och snyggare. 

Programkod ska se ut som exemplet nedan. Koden måste vara korrekt indenterad då den blir lättare att läsa vilket gör det lättare att hitta syntaktiska fel.

```
Ändring 1
<resources>
    <string name="app_name">To-Do List Appen</string>
</resources>

Ändring 2
android:text="Välkommen till denna fantatiska app där man ska göra listor med antingen saker man har gjort eller har saker och göra."

Ändring 3
<uses-permission android:name="android.permission.INTERNET" />

Detta är dem tre följande ändringarna som har gjorts på första frågan. byta appnamnet på titlen, sedan så ändrad jag android texten som fanns på appen och sedan gav jag internet återkomst till appen för det var några saker som man har lärt sig innan.

Ändrade vilken layout som ska användas.
<androidx.constraintlayout.widget.ConstraintLayout

Detta är koden för dem två sista frågorna där det har lagts till Button, Edittext och Imageview samt så har widgets använts margin attribut så att varje widget och attribut har en bra placering samt så har jag 2 screenshots på hur det såg ut innan jag ändrade dem sista widgets och placeringarna och hur dem ändringarna såg ut.
    <TextView
        android:id="@+id/textView"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:text="Välkommen till denna fantastiska app där man ska göra listor med antingen saker man har gjort eller har saker och göra."
        app:layout_constraintTop_toTopOf="parent"
        app:layout_constraintStart_toStartOf="parent"
        app:layout_constraintEnd_toEndOf="parent"
        android:layout_marginTop="16dp"/>

    <Button
        android:id="@+id/button"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:text="Tryck här för att spara."
        app:layout_constraintStart_toStartOf="parent"
        app:layout_constraintTop_toBottomOf="@id/textView"
        android:layout_marginTop="16dp"
        android:layout_marginStart="16dp"/>

    <EditText
        android:id="@+id/editText"
        android:layout_width="0dp"
        android:layout_height="wrap_content"
        android:hint="Skriv vad du vill lägga till i listan."
        app:layout_constraintStart_toStartOf="parent"
        app:layout_constraintEnd_toEndOf="parent"
        app:layout_constraintTop_toBottomOf="@id/button"
        android:layout_marginTop="16dp"
        android:layout_marginStart="16dp"
        android:layout_marginEnd="16dp"/>

    <ImageView
        android:id="@+id/imageView"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        app:srcCompat="@android:drawable/ic_menu_gallery"
        app:layout_constraintStart_toStartOf="parent"
        app:layout_constraintTop_toBottomOf="@id/editText"
        android:layout_marginTop="16dp"
        android:layout_marginStart="16dp"/>


```

Bilder läggs i samma mapp som markdown-filen.

![](android.png)
![](android2.png)
![](android3.png)

Läs gärna:

- Boulos, M.N.K., Warren, J., Gong, J. & Yue, P. (2010) Web GIS in practice VIII: HTML5 and the canvas element for interactive online mapping. International journal of health geographics 9, 14. Shin, Y. &
- Wunsche, B.C. (2013) A smartphone-based golf simulation exercise game for supporting arthritis patients. 2013 28th International Conference of Image and Vision Computing New Zealand (IVCNZ), IEEE, pp. 459–464.
- Wohlin, C., Runeson, P., Höst, M., Ohlsson, M.C., Regnell, B., Wesslén, A. (2012) Experimentation in Software Engineering, Berlin, Heidelberg: Springer Berlin Heidelberg.
