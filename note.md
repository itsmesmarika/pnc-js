# Making table 

**Html**

```
 
        <table border="1">
            
            <thead>
                <th>NAME</th>
                <th>CLASS</th>
                <th>ROLLNO</th>
                <th>SECTION</th>

            </thead>
            <tbody>
                <tr>
                    <td>SMarika</td>
                    <td>14</td>
                    <td>32</td>
                    <td>A</td>

                </tr>
                <tr>
                    <td>Saugat</td>
                    <td>14</td>
                    <td>21</td>
                    <td>A</td>
                
                </tr>
                <tr>
                    <td>Anish</td>
                    <td>11</td>
                    <td>31</td>
                    <td>D</td>
                </tr>
                <tr>
                    <td>Bishal</td>
                    <td>12</td>
                    <td>2</td>
                    <td>D</td>
                </tr>
            </tbody>

        </table>

 ```

# Mapping

**This is how we do mapping**

- photo rakkhna ko laagi pahila img tag lekhni
- opening tag ko src vanni attribute maa photo ko link rakhni
- alt attributes vaneko image dekhiyena vani alt maa tyo photo k ho vani text lekhinxa    
- usemap attritube chai image tag vitrai lekhni kinaki tyo photo lai path dini
- map tag chai photo maa click garna ko laagi use huncha
- area tag vitra chai shape coords href haru attriutes use hunxa jo chai kahaa click gardaa kun link maa connect garni vanera rakheko
 
```
<img src="https://english.onlinekhabar.com/wp-content/uploads/2016/03/Sher-3.jpg" alt="deuba" usemap="#deuba">
<map name="deuba">
    <area shape="rect" coords="220,80,350,500" href="https://en.wikipedia.org/wiki/Sher_Bahadur_Deuba">
</map>



```
