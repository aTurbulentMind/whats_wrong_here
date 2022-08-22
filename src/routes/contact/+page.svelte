<script>
         
        // Get HTML head element
        var head = document.getElementsByTagName('HEAD')[0];
 
        // Create new link Element
        var link = document.createElement('link');
 
        // set the attributes for link element
        link.rel = 'stylesheet';
     
        link.type = 'text/css';
     
        link.href = '/src/lib/basecamp.css';
 
        // Append link element to HTML head
        head.appendChild(link);
    </script>


<h1>Is it working yet?</h1>

<style lang="scss">
    @import '../src/lib/basecamp';
</style>