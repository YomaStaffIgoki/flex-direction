# flex-direction
just a practise on how to use flex directions effectively


<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <style>
.group1,.group2,.group3
{
        display: flex;
        flex-wrap: wrap;
        flex-direction: row;
        justify-content: space-evenly;
    }
   
.first
    {
        width:24%;
        padding: 10px;
        border-radius: 5px;
        border:1px solid blue;
        margin-bottom: 10px;
    }

</style>
</head>
<body>
    <div class="group1">
        <div class="first">
            <p><strong>Image Optimisation</strong></p>
            <p> < image >  and Automatic Image </p>
            <p> Optimisation with instant builds</p>
                <a href="#">Documentation &rarr;</a>
        </div> 

        <div class="first">
            <p><strong>Internationalization</strong></p>
            <p> Built-in Domain and SubDomain Routine and </p>
               <p>Automatic Language Detection </p>
                <a href="#">Documentation &rarr;</a>
                </div>

       <div class="first">
        <p><strong>Next.js Analytics</strong></p>
        <p>A true lighthouse score based on real </p>
           <p> visitor data and page-by-page insight</p>
            <a href="#">Documentation &rarr;</a>
        </div>
    </div>    

        
      

    <div class="group2">
    <div class="first">
        <p><strong>Zero Config</strong></p>
            <p> compilation and bundling.</p> 
     </p> Optimized for production from the start</p>
            <a href="#">Documentation &rarr;</a>
            </div>

        <div class="first">
        <p><strong>Hybrid:SSG and SSR</strong></p>
        <p> Pre-render pages at build time (SSG) or </p>
           <p> Request Time (SSR) in a single project</p>
            <a href="#">Documentation &rarr;</a>
        </div>

        <div class="first">
            <p><strong>Incremental Static Regeneration</strong></p>
            <p>  Add and update statically pre-rendered pages</p>
              <p>  incrementally after build time.</p>
                <a href="#">Documentation &rarr;</a>
              </div> 
    </div>
          
    <div class="group3">
              <div class="first">
                <p><strong> TypeScript Support</strong></p>
 <p>Automatic TypeScript configuration and</p>
 <p>compilation.</p>
     <a href="#">Documentation &rarr;</a>
                 </div>
                 <div class="first">
                    <p><strong>Fast Refresh</strong></p>
                        <p>Fast, reliable live-editing experience, as</p>
                        <p> proven at Facebook scale..</p>
                        <a href="#">Documentation &rarr;</a>
                     </div>
                   
                     <div class="first">
                     <p><strong>File-system Routing</strong></p>
                        <p>Every component in the pages</p>
                     <p>directory becomes a route.</p>
                        <a href="#">Documentation →</a>
                        </div>
    </div>     
</body>
</html>
