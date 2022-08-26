<a href="https://biasorter.tumblr.com/post/175232387900/sorter-code-and-instructions-to-it">source code for the sorter</a>

<h2>to add a group to the list:</h2>

- add a new array in <code>const bands</code> in the format
```
band_name: new Array(
    "member1",
    "member2",
    ...
    "memberx"
),
```
you can look for <code>>>>> add band here <<<<</code>
- add a button in <code>table id="bandChoice"</code> in the format:
```
<td>
    <button id="band_name_button" onclick="add_group(bands.band_name, 'band_name');" style="text-align:center;">band_name</button>
</td>
```
you can look for <code>>>>> add button here <<<<</code>