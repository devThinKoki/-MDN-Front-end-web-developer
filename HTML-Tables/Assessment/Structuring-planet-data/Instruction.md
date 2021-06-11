<h1>Project brief</h1>
<p>You are working at a school; currently your students are studying the planets of our solar system, and you want to provide them with an easy-to-follow set of data to look up facts and figures about the planets. An HTML data table would be ideal — you need to take the raw data you have available and turn it into a table, following the steps below.</p>
<p>The finished table should look like this:</p>
<img src="https://developer.mozilla.org/en-US/docs/Learn/HTML/Tables/Structuring_planet_data/assessment-table.png">
You can also <a href="https://mdn.github.io/learning-area/html/tables/assessment-finished/planets-data.html">see the example live here</a>

<h2>Steps to complete</h2>
<p>The following steps describe what you need to do to complete the table example. All the data you'll need is contained in the planets-data.txt file. If you have trouble visualising the data, look at the live example above, or try drawing a diagram.</p>

<ol>
    <li>Open your copy of blank-template.html, and start the table off by giving it an outer container, a table header, and a table body. You don't need a table footer for this example.</li>
    <li>Add the provided caption to your table.</li>
    <li>Add a row to the table header containing all the column headers.</li>
    <li>Create all the content rows inside the table body, remembering to make all the row headings into headings semantically.</li>
    <li>Ensure all the content is placed into the right cells — in the raw data, each row of planet data is shown next to its associated planet.</li>
    <li>Add attributes to make the row and column headers unambiguously associated with the rows, columns, or rowgroups that they act as headings for.</li>
    <li>Add a black border just around the column that contains all the planet name row headers.</li>
</ol>

<h2>Hints and tips</h2>
<ol>
    <li>The first cell of the header row needs to be blank, and span two columns.</li>
    <li>The group row headings (e.g. Jovian planets) that sit to the left of the planet name row headings (e.g. Saturn) are a little tricky to sort out — you need to make sure each one spans the correct number of rows and columns.</li>
    <li>One way of associating headers with their rows/columns is a lot easier than the other way.</li>
</ol>