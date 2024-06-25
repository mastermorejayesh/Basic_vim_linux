<h1> Basic linux/Unix Vim/vi Commands </h1>

To jump last line of the file : Shift + g (captial G)
**************************************************************************************************************
To jump top line of the file : small - gg
**************************************************************************************************************
To jump last word of the line : shift + a
**************************************************************************************************************
To jump frist word of the line : shift + i
**************************************************************************************************************

<h3>Replace and undo</h3>

: %s/word which to replace/word want to replace /g
Undo : u
**************************************************************************************************************

<h3>Search</h3>

top to bottom search
Serch a word in file :/word
Serch a next word in file when serching : n
**************************************************************************************************************

<h3>Bottom to top search </h3>
  
Serch a word in file :?word

**************************************************************************************************************
search a world appers in cursor : *
search a revers world appers in cursor : #
**************************************************************************************************************

<h3>Delete</h3>

delete/cut single line : dd
delete line after 10 rows : 10dd
delete whole data: esc + gg + d + shit + g
**************************************************************************************************************

<h3>cut/pest</h3>

cut : dd
pest : p {below the cursor}
pest : shift + p {above the cursor}
**************************************************************************************************************

<h3>copy/pest</h3>

select one whole line : shift + v
select whole line or multipal  data : small-v(visual mode)
copy selected data : small-y (yanked)
pest : small-p
**************************************************************************************************************
set line number in our file : set nu --
(it is only temporery given lines if we save this file with nu line this not saved it is only temp)
remove set line number in our file : set nonu
****************************************************************************************************************
view multipal files at same time : vim -o file_no_1 file_no_2
working with vim -o  shift cursor to  anathor file : crtrl + w (twice)
***************************************************************************************************************
compair file 
check difference between multipal files : vim -d file_no_1 file_no_2



