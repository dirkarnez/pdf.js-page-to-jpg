<!DOCTYPE html>
<html>
<head>
<title>Page Title</title>
</head>
<body>

<script src="http://cdnjs.cloudflare.com/ajax/libs/processing.js/1.4.1/processing-api.min.js"></script><html>
<!--
  Created using jsbin.com
  Source can be edited via http://jsbin.com/pdfjs-helloworld-v2/8598/edit
-->
<body>
  <canvas id="the-canvas" style="border:1px solid black"></canvas>
  <input id='pdf' type='file'/>

  <!-- Use latest PDF.js build from Github -->
<script src="https://cdnjs.cloudflare.com/ajax/libs/pdf.js/2.6.347/pdf.min.js" integrity="sha512-Z8CqofpIcnJN80feS2uccz+pXWgZzeKxDsDNMD/dJ6997/LSRY+W4NmEt9acwR+Gt9OHN0kkI1CTianCwoqcjQ==" crossorigin="anonymous" referrerpolicy="no-referrer"></script>
  <script type="text/javascript">

    //
    // Disable workers to avoid yet another cross-origin issue (workers need the URL of
    // the script to be loaded, and dynamically loading a cross-origin script does
    // not work)
    //
    //PDFJS.disableWorker = true;
debugger;
    //
    // Asynchronous download PDF as an ArrayBuffer
    //
    var pdf = document.getElementById('pdf');
    pdf.onchange = function(ev) {
            debugger;
      if (file = document.getElementById('pdf').files[0]) {
        fileReader = new FileReader();
        fileReader.onload = function(ev) {
          console.log(ev);
          pdfjsLib.getDocument(fileReader.result).promise.then(function getPdfHelloWorld(pdf) {
          debugger;
            //
            // Fetch the first page
            //
            console.log(pdf)
            pdf.getPage(1).then(function getPageHelloWorld(page) {
              var scale = 1.5;
              var viewport = page.getViewport(scale);

              //
              // Prepare canvas using PDF page dimensions
              //
              var canvas = document.getElementById('the-canvas');
              var context = canvas.getContext('2d');
              canvas.height = viewport.height;
              canvas.width = viewport.width;

              //
              // Render PDF page into canvas context
              //
              var task = page.render({canvasContext: context, viewport: viewport})
              task.promise.then(function(){
                console.log(canvas.toDataURL('image/jpeg'));
              });
            });
          }, function(error){
            console.log(error);
          });
        };
        fileReader.readAsArrayBuffer(file);
      }
    }
  </script>
  

<style id="jsbin-css">

</style>
<script>

</script>
</body>
</html>

</body>
</html>


