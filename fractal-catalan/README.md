<link rel="stylesheet" href="../scripts/style.css">
<meta charset="utf-8">
<link rel="icon" type="image/png" href="vr/salas/imagens/icone.png">
<h2>Visualization of Polyhedra with Virtual Reality (VR) in A-frame</h2>
 <b>author:</b> Paulo Henrique Siqueira - Universidade Federal do Paraná
 <br><b>contact:</b> <a href="#">paulohscwb@gmail.com</a>
 <br><a href="https://paulohscwb.github.io/polyhedra3/fractal-catalan/pt-br/">versão em português</a>
 <form style="margin: 0 auto; float:right; text-align:right; width:100%; margin-bottom:15px;">
	<select id="url" onchange="urlHandler(this.value)" style="color:royalblue;">
		<option disabled selected value>More solids:</option>
		<option value="../catalangems/">Catalan gems</option>
		<option value="../dragon-archimedes/">Archimedes and Catalan Dragon Fractals</option>
		<option value="../kites/">Star kites</option>
		<option value="../araucaria/">Araucaria with polyhedrons</option>
		<option value="../dragon-nonconvex/">Dragon fractals of non-convex polyhedra</option>
		<option disabled value="../fractal-catalan/">Catalan fractals</option>
		<!--<option value="../deltahedra/">Deltahedra</option>
		<option value="../unicorn-platonic/">Plato's Unicorn Fractals</option>
		<option value="../dragon-catalan/">Catalan Dragon Fractals</option>
		<option value="../fractalnonconvex1/">Fractals of non-convex polyhedra</option>
		<option value="../truncated-archimedes/">Truncated Archimedean polyhedra</option>
		<option value="../unicorn-catalan/">Catalan Unicorn Fractals</option>
		<option value="../fractalnonconvex2/">Fractals of non-convex polyhedra 2</option>
		<option value="../unicorn-archimedes/">Archimedes Unicorn Fractals</option>
		<option value="../fractalnonconvex3/">Fractals of non-convex polyhedra 3</option>
		<option value="../truncated-catalan/">Truncated Catalan polyhedra</option>
		<option value="../unicorn-nonconvex1/">Unicorn fractals of non-convex polyhedra</option>
		<option value="../dragon-nonconvex2/">Dragon fractals of non-convex polyhedra 2</option>
		<option value="../unicorn-nonconvex2/">Unicorn fractals of non-convex polyhedra 2</option>
		<option value="../fractalnonconvex4/">Fractals of non-convex polyhedra 4</option>
		<option value="../dragon-nonconvex3/">Dragon fractals of non-convex polyhedra 3</option>
		<option value="../fractalnonconvex5/">Fractals of non-convex polyhedra 5</option>
		<option value="../unicorn-nonconvex3/">Unicorn fractals of non-convex polyhedra 3</option>
		<option value="../fractalnonconvex6/">Fractals of non-convex polyhedra 6</option>-->
	</select>
</form>
<script>
function urlHandler(value) {                               
    window.location.assign(`${value}`);
}
</script>

<p id="p1"></p>
  <h2 align="center"><img src="vr/salas/imagens/icone.png" style="margin-bottom:-10px" width="45"> Catalan fractals</h2>
  Using the same principle as the construction of the Sierpinski triangle or the Koch curve, we can construct fractals from other regular polygons. When these polygons form a polyhedron, we have the construction of a fractal polyhedron.
<br>This work shows Catalan and some Archimedean polyhedra forming fractals, modeled for visualization in Virtual Reality.
<p align="center"><a href="#m3d">3D Models</a><span>&nbsp;&nbsp;|&nbsp;&nbsp;</span><a href="../">Home</a></p>
<hr>
 <p align="center"><img src="vr/salas/videos/catalan1.gif" style="max-width: 45%; border-radius:5px; margin-right:15px" loading="lazy" alt="RV de fractais"/><img src="vr/salas/videos/catalan2.gif" style="max-width: 45%; border-radius:5px;" loading="lazy" alt="RV de fractais"/></p> 
<hr>
<h3 id="m3d" align="center">3D models</h3>
<!--<iframe width="560" height="315" style="max-width:100%" src="https://www.youtube.com/embed/videoseries?list=PLy0I_lGW8HxWGmFjnLlbixXP2VZLbEBW3" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>-->
<h4>1. Deltoidal hexecontahedron</h4>
<a href="vr/DeltoidalHexecontahedron.htm" target="_blank" title="3D model" class="fotoA"><img src="ar/1A.png" class="foto" alt="Deltoidal Hexecontahedron fractal"></a>
 <br>Applying the construction principle of the Koch curve to faces of the deltoidal hexecontahedron, we obtain a deltoidal hexecontahedron fractal. In the first order of fractal construction, we construct a new solid at 20 vertices of the original polyhedron. In this example, we have representations of the solid in orders 0, 1, 2 and 3.
 <table margin="auto">
	<tr>
		<th>order</th>
		<th>polyhedra</th>
		<th>faces</th>
		<th>edges</th>
		<th>vertices</th>
	</tr>
	<tr>
		<td>0</td>
		<td>1</td>
		<td>60</td>
		<td>120</td>
		<td>62</td>
	</tr>
	<tr>
		<td>1</td>
		<td>21</td>
		<td>1260</td>
		<td>2520</td>
		<td>1302</td>
	</tr>
	<tr>
		<td>2</td>
		<td>441</td>
		<td>26460</td>
		<td>52920</td>
		<td>27342</td>
	</tr>
	<tr>
		<td>3</td>
		<td>9261</td>
		<td>555660</td>
		<td>1111320</td>
		<td>574182</td>
	</tr>
 </table>
 <br>
<hr>
<h4>2. Deltoidal icositetrahedron</h4>
<a href="vr/DeltoidalIcositetrahedron.htm" target="_blank" title="3D model" class="fotoA"><img src="ar/2A.png" class="foto" alt="Deltoidal icositetrahedron fractal"></a>
 <br>Applying the construction principle of the Sierpinski curve to faces of the deltoidal icositetrahedron, we obtain a deltoidal icositetrahedron fractal. In the first order of fractal construction, we construct a new solid at 6 vertices of the original polyhedron. In this example, we have representations of the solid in orders 0, 1, 2, 3 and 4.
 <table margin="auto">
	<tr>
		<th>order</th>
		<th>polyhedra</th>
		<th>faces</th>
		<th>edges</th>
		<th>vertices</th>
	</tr>
	<tr>
		<td>0</td>
		<td>1</td>
		<td>24</td>
		<td>48</td>
		<td>26</td>
	</tr>
	<tr>
		<td>1</td>
		<td>6</td>
		<td>144</td>
		<td>288</td>
		<td>156</td>
	</tr>
	<tr>
		<td>2</td>
		<td>36</td>
		<td>864</td>
		<td>1728</td>
		<td>936</td>
	</tr>
	<tr>
		<td>3</td>
		<td>216</td>
		<td>5184</td>
		<td>10368</td>
		<td>5616</td>
	</tr>
	<tr>
		<td>4</td>
		<td>1296</td>
		<td>31104</td>
		<td>62208</td>
		<td>33696</td>
	</tr>
 </table>
<hr>
<h4>3. Disdyakis dodecahedron</h4>
<a href="vr/DisdyakisDodecahedron.htm" target="_blank" title="3D model" class="fotoA"><img src="ar/3A.png" class="foto" alt="Disdyakis dodecahedron fractal"></a>
 <br>Applying the construction principle of the Sierpinski curve to faces of the disdyakis dodecahedron, we obtain a disdyakis dodecahedron fractal. In the first order of fractal construction, we construct a new solid at 6 vertices of the original polyhedron. In this example, we have representations of the solid in orders 0, 1, 2, 3 and 4.
 <table margin="auto">
	<tr>
		<th>order</th>
		<th>polyhedra</th>
		<th>faces</th>
		<th>edges</th>
		<th>vertices</th>
	</tr>
	<tr>
		<td>0</td>
		<td>1</td>
		<td>48</td>
		<td>72</td>
		<td>26</td>
	</tr>
	<tr>
		<td>1</td>
		<td>6</td>
		<td>288</td>
		<td>432</td>
		<td>156</td>
	</tr>
	<tr>
		<td>2</td>
		<td>36</td>
		<td>1728</td>
		<td>2592</td>
		<td>936</td>
	</tr>
	<tr>
		<td>3</td>
		<td>216</td>
		<td>10368</td>
		<td>15552</td>
		<td>5616</td>
	</tr>
	<tr>
		<td>4</td>
		<td>1296</td>
		<td>62208</td>
		<td>93312</td>
		<td>33696</td>
	</tr>
 </table>
 <br>
<hr>
<h4>4. Disdyakis triacontahedron</h4>
<a href="vr/DisdyakisTriacontahedron.htm" target="_blank" title="3D model" class="fotoA"><img src="ar/4A.png" class="foto" alt="Disdyakis triacontahedron fractal"></a>
 <br>Applying the construction principle of the Koch curve to faces of the disdyakis triacontahedron, we obtain a disdyakis triacontahedron fractal. In the first order of fractal construction, we construct a new solid at 20 vertices of the original polyhedron. In this example, we have representations of the solid in orders 0, 1, 2 and 3.
 <table margin="auto">
	<tr>
		<th>order</th>
		<th>polyhedra</th>
		<th>faces</th>
		<th>edges</th>
		<th>vertices</th>
	</tr>
	<tr>
		<td>0</td>
		<td>1</td>
		<td>120</td>
		<td>180</td>
		<td>62</td>
	</tr>
	<tr>
		<td>1</td>
		<td>21</td>
		<td>2520</td>
		<td>3780</td>
		<td>1302</td>
	</tr>
	<tr>
		<td>2</td>
		<td>441</td>
		<td>52920</td>
		<td>79380</td>
		<td>27342</td>
	</tr>
	<tr>
		<td>3</td>
		<td>9261</td>
		<td>1111320</td>
		<td>1666980</td>
		<td>574182</td>
	</tr>
 </table>
 <br>
<hr>
<h4>5. Pentagonal hexecontahedron</h4>
<a href="vr/PentagonalHexecontahedron.htm" target="_blank" title="3D model" class="fotoA"><img src="ar/5A.png" class="foto" alt="Pentagonal hexecontahedron fractal"></a>
 <br>Applying the construction principle of the Koch curve to faces of the pentagonal hexecontahedron, we obtain a pentagonal hexecontahedron fractal. In the first order of fractal construction, we construct a new solid at 20 vertices of the original polyhedron. In this example, we have representations of the solid in orders 0, 1, 2 and 3.
 <table margin="auto">
	<tr>
		<th>order</th>
		<th>polyhedra</th>
		<th>faces</th>
		<th>edges</th>
		<th>vertices</th>
	</tr>
	<tr>
		<td>0</td>
		<td>1</td>
		<td>60</td>
		<td>150</td>
		<td>92</td>
	</tr>
	<tr>
		<td>1</td>
		<td>21</td>
		<td>1260</td>
		<td>3150</td>
		<td>1932</td>
	</tr>
	<tr>
		<td>2</td>
		<td>441</td>
		<td>26460</td>
		<td>66150</td>
		<td>40572</td>
	</tr>
	<tr>
		<td>3</td>
		<td>9261</td>
		<td>555660</td>
		<td>1389150</td>
		<td>852012</td>
	</tr>
 </table>
 <br>
<hr>
<h4>6. Pentagonal icositetrahedron</h4>
<a href="vr/PentagonalIcositetrahedron.htm" target="_blank" title="3D model" class="fotoA"><img src="ar/6A.png" class="foto" alt="Pentagonal icositetrahedron fractal"></a>
 <br>Applying the construction principle of the Sierpinski curve to faces of the pentagonal icositetrahedron, we obtain a pentagonal icositetrahedron fractal. In the first order of fractal construction, we construct a new solid at 8 vertices of the original polyhedron. In this example, we have representations of the solid in orders 0, 1, 2 and 3.
 <table margin="auto">
	<tr>
		<th>order</th>
		<th>polyhedra</th>
		<th>faces</th>
		<th>edges</th>
		<th>vertices</th>
	</tr>
	<tr>
		<td>0</td>
		<td>1</td>
		<td>24</td>
		<td>60</td>
		<td>38</td>
	</tr>
	<tr>
		<td>1</td>
		<td>8</td>
		<td>192</td>
		<td>480</td>
		<td>304</td>
	</tr>
	<tr>
		<td>2</td>
		<td>64</td>
		<td>1536</td>
		<td>3840</td>
		<td>2432</td>
	</tr>
	<tr>
		<td>3</td>
		<td>512</td>
		<td>12288</td>
		<td>30720</td>
		<td>19456</td>
	</tr>
 </table>
 <br>
<hr>
<h4>7. Pentakis dodecahedron</h4>
<a href="vr/PentakisDodecahedron.htm" target="_blank" title="3D model" class="fotoA"><img src="ar/7A.png" class="foto" alt="Pentakis dodecahedron fractal"></a>
 <br>Applying the construction principle of the Koch curve to faces of the pentakis dodecahedron, we obtain a pentakis dodecahedron fractal. In the first order of fractal construction, we construct a new solid at 20 vertices of the original polyhedron. In this example, we have representations of the solid in orders 0, 1, 2 and 3.
 <table margin="auto">
	<tr>
		<th>order</th>
		<th>polyhedra</th>
		<th>faces</th>
		<th>edges</th>
		<th>vertices</th>
	</tr>
	<tr>
		<td>0</td>
		<td>1</td>
		<td>60</td>
		<td>90</td>
		<td>32</td>
	</tr>
	<tr>
		<td>1</td>
		<td>21</td>
		<td>1260</td>
		<td>1890</td>
		<td>672</td>
	</tr>
	<tr>
		<td>2</td>
		<td>441</td>
		<td>26460</td>
		<td>39690</td>
		<td>14112</td>
	</tr>
	<tr>
		<td>3</td>
		<td>9261</td>
		<td>555660</td>
		<td>833490</td>
		<td>296352</td>
	</tr>
 </table>
 <br>
<hr>
<h4>8. Rhombic dodecahedron</h4>
<a href="vr/RhombicDodecahedron.htm" target="_blank" title="3D model" class="fotoA"><img src="ar/8A.png" class="foto" alt="Rhombic Dodecahedron fractal"></a>
 <br>Applying the construction principle of the Sierpinski curve to faces of the rhombic dodecahedron, we obtain a rhombic dodecahedron fractal. In the first order of fractal construction, we construct a new solid at 6 vertices of the original polyhedron. In this example, we have representations of the solid in orders 0, 1, 2, 3 and 4.
 <table margin="auto">
	<tr>
		<th>order</th>
		<th>polyhedra</th>
		<th>faces</th>
		<th>edges</th>
		<th>vertices</th>
	</tr>
	<tr>
		<td>0</td>
		<td>1</td>
		<td>12</td>
		<td>24</td>
		<td>14</td>
	</tr>
	<tr>
		<td>1</td>
		<td>6</td>
		<td>72</td>
		<td>144</td>
		<td>84</td>
	</tr>
	<tr>
		<td>2</td>
		<td>36</td>
		<td>432</td>
		<td>864</td>
		<td>504</td>
	</tr>
	<tr>
		<td>3</td>
		<td>216</td>
		<td>2592</td>
		<td>5184</td>
		<td>3024</td>
	</tr>
	<tr>
		<td>4</td>
		<td>1296</td>
		<td>15552</td>
		<td>31104</td>
		<td>18144</td>
	</tr>
 </table>
 <br>
<hr>
<h4>9. Archimedean rhombicosidodecahedron</h4>
<a href="vr/Rhombicosidodecahedron2.htm" target="_blank" title="3D model" class="fotoA"><img src="ar/9A.png" class="foto" alt="Rhombicosidodecahedron fractal"></a>
 <br>Applying the construction principle of the Koch curve to faces of the rhombicosidodecahedron, we obtain a rhombicosidodecahedron fractal. In the first order of fractal construction, we construct a new solid at 20 vertices of the original polyhedron. In this example, we have representations of the solid in orders 0, 1, 2 and 3.
 <table margin="auto">
	<tr>
		<th>order</th>
		<th>polyhedra</th>
		<th>faces</th>
		<th>edges</th>
		<th>vertices</th>
	</tr>
	<tr>
		<td>0</td>
		<td>1</td>
		<td>62</td>
		<td>120</td>
		<td>60</td>
	</tr>
	<tr>
		<td>1</td>
		<td>21</td>
		<td>1302</td>
		<td>2520</td>
		<td>1260</td>
	</tr>
	<tr>
		<td>2</td>
		<td>441</td>
		<td>27342</td>
		<td>52920</td>
		<td>26460</td>
	</tr>
	<tr>
		<td>3</td>
		<td>9261</td>
		<td>574182</td>
		<td>1111320</td>
		<td>555660</td>
	</tr>
 </table>
 <br>
<hr>
<h4>10. Rhombic triacontahedron</h4>
<a href="vr/RhombicTriacontahedron.htm" target="_blank" title="3D model" class="fotoA"><img src="ar/10A.png" class="foto" alt="Great triakis icosahedron dragon fractal"></a>
 <br>Applying the construction principle of the Koch curve to faces of the rhombic triacontahedron, we obtain a rhombic triacontahedron fractal. In the first order of fractal construction, we construct a new solid at 20 vertices of the original polyhedron. In this example, we have representations of the solid in orders 0, 1, 2 and 3.
 <table margin="auto">
	<tr>
		<th>order</th>
		<th>polyhedra</th>
		<th>faces</th>
		<th>edges</th>
		<th>vertices</th>
	</tr>
	<tr>
		<td>0</td>
		<td>1</td>
		<td>30</td>
		<td>60</td>
		<td>32</td>
	</tr>
	<tr>
		<td>1</td>
		<td>21</td>
		<td>630</td>
		<td>1260</td>
		<td>672</td>
	</tr>
	<tr>
		<td>2</td>
		<td>441</td>
		<td>13230</td>
		<td>26460</td>
		<td>14112</td>
	</tr>
	<tr>
		<td>3</td>
		<td>9261</td>
		<td>277830</td>
		<td>555660</td>
		<td>296352</td>
	</tr>
 </table>
 <br>
<hr>
<p class="topop"><a href="#p1" class="topo">back to top</a></p>
<h4>11. Archimedean snub dodecahedron</h4>
<a href="vr/SnubDodecahedron2.htm" target="_blank" title="3D model" class="fotoA"><img src="ar/11A.png" class="foto" alt="Great triakis octahedron dragon fractal"></a>
 <br>Applying the construction principle of the Koch curve to faces of the snub dodecahedron, we obtain a snub dodecahedron fractal. In the first order of fractal construction, we construct a new solid at 20 vertices of the original polyhedron. In this example, we have representations of the solid in orders 0, 1, 2 and 3.
 <table margin="auto">
	<tr>
		<th>order</th>
		<th>polyhedra</th>
		<th>faces</th>
		<th>edges</th>
		<th>vertices</th>
	</tr>
	<tr>
		<td>0</td>
		<td>1</td>
		<td>92</td>
		<td>150</td>
		<td>60</td>
	</tr>
	<tr>
		<td>1</td>
		<td>21</td>
		<td>1932</td>
		<td>3150</td>
		<td>1260</td>
	</tr>
	<tr>
		<td>2</td>
		<td>441</td>
		<td>40572</td>
		<td>66150</td>
		<td>26460</td>
	</tr>
	<tr>
		<td>3</td>
		<td>9261</td>
		<td>852012</td>
		<td>1389150</td>
		<td>555660</td>
	</tr>
 </table>
 <br>
<hr>
<h4>12. Tetrakis hexahedron - Menger sponge</h4>
<a href="vr/TetrakisHexahedron.htm" target="_blank" title="3D model" class="fotoA"><img src="ar/12A.png" class="foto" alt="Tetrakis hexahedron - Menger sponge fractal"></a>
 <br>Applying the construction principle of the Sierpinski carpet to tetrakis hexahedron faces, we obtain a tetrakis hexahedron fractal. In the first order of construction of the fractal, we construct 8 new solids on each face of the original polyhedron, all with ⅓ the measurement of the tetrakis hexahedron’s edge. In this example, we have representations of the solid in orders 0, 1, 2 and 3.
<hr>
<h4>13. Tetrakis hexahedron - Menger's Cross Jerusalem</h4>
<a href="vr/TetrakisHexahedron2.htm" target="_blank" title="3D model" class="fotoA"><img src="ar/13A.png" class="foto" alt="Tetrakis hexahedron - Menger's Cross Jerusalem fractal"></a>
 <br>Consider a tetrakis hexahedron. We can increase the edge sizes of the corner tetrakis hexahedrons and decrease the edge sizes of the intermediate tetrakis hexahedrons to reveal a cross. In this version, we have 8 homothetic tetrakis hexahedrons with an aspect ratio of ⅖ and 12 homothetic tetrakis hexahedrons with a proportion of ⅕. 
<hr>
<h4>14. Tetrakis hexahedron - Menger's Cross Jerusalem v2</h4>
<a href="vr/TetrakisHexahedron3.htm" target="_blank" title="3D model" class="fotoA"><img src="ar/14A.png" class="foto" alt="Tetrakis hexahedron - Menger's Cross Jerusalem fractal"></a>
 <br>Consider a tetrakis hexahedron. We can increase the edge sizes of the corner tetrakis hexahedrons and decrease the edge sizes of the intermediate tetrakis hexahedrons to reveal a cross. In this version, we have 8 homothetic tetrakis hexahedrons with an aspect ratio of √2 - 1 and 12 homothetic tetrakis hexahedrons with a proportion of (√2 - 1)². 
<hr>
<h4>15. Tetrakis hexahedron - Mosely snowflake</h4>
<a href="vr/TetrakisHexahedron4.htm" target="_blank" title="3D model" class="fotoA"><img src="ar/15A.png" class="foto" alt="Tetrakis hexahedron - Mosely snowflake fractal"></a>
 <br>The Mosely snowflake is a type of Sierpinski-Menger fractal obtained in two variants by the operation used in creating the Sierpinski-Menger snowflake. In this case, we removed eight corner tetrakis hexahedrons and the center tetrakis hexahedron in each iteration. 
<hr>
<h4>16. Triangular fractal tree with pentakis dodecahedrons</h4>
<a href="vr/Tree0.htm" target="_blank" title="3D model" class="fotoA"><img src="ar/16A.png" class="foto" alt="Triangular fractal tree with pentakis dodecahedrons"></a>
 <br>Applying the principle of repetitions with cone frustum, we obtain a fractal tree. In this example, we added pentakis dodecahedrons as the “fruits” or “flowers” of the tree. In the first order of construction the fractal, we build three new cone frustums connected with a face of the original cone frustum. In this example, we have solid representations in orders from 0 to 6. 
 <br>
<hr>
<h4>17. Pentagonal fractal tree with pentakis dodecahedrons</h4>
<a href="vr/Tree0a.htm" target="_blank" title="3D model" class="fotoA"><img src="ar/17A.png" class="foto" alt="Pentagonal fractal tree with pentakis dodecahedrons"></a>
 <br>Applying the principle of repetitions with cone frustum, we obtain a fractal tree. In this example, we added pentakis dodecahedrons as the “fruits” or “flowers” of the tree. In the first order of construction the fractal, we build three new cone frustums connected with a face of the original cone frustum. In this example, we have solid representations in orders from 0 to 5. 
 <br>
<hr>
<h4>18. Triangular fractal tree with rhombic triacontahedrons</h4>
<a href="vr/Tree1.html" target="_blank" title="3D model" class="fotoA"><img src="ar/18A.png" class="foto" alt="Triangular fractal tree with rhombic triacontahedrons"></a>
 <br>Applying the principle of repetitions with cone frustum, we obtain a fractal tree. In this example, we added rhombic triacontahedrons as the “fruits” or “flowers” of the tree. In the first order of construction the fractal, we build three new cone frustums connected with a face of the original cone frustum. In this example, we have solid representations in orders from 0 to 6. 
 <br>
<hr>
<h4>19. Pentagonal fractal tree with rhombic triacontahedrons</h4>
<a href="vr/Tree1a.htm" target="_blank" title="3D model" class="fotoA"><img src="ar/19A.png" class="foto" alt="Pentagonal fractal tree with rhombic triacontahedrons"></a>
 <br>Applying the principle of repetitions with cone frustum, we obtain a fractal tree. In this example, we added rhombic triacontahedrons as the “fruits” or “flowers” of the tree. In the first order of construction the fractal, we build three new cone frustums connected with a face of the original cone frustum. In this example, we have solid representations in orders from 0 to 5. 
 <br>
<hr>
<h4>20. Triangular fractal tree with triakis icosahedrons</h4>
<a href="vr/Tree2.html" target="_blank" title="3D model" class="fotoA"><img src="ar/20A.png" class="foto" alt="Triangular fractal tree with triakis icosahedrons"></a>
 <br>Applying the principle of repetitions with cone frustum, we obtain a fractal tree. In this example, we added triakis icosahedrons as the “fruits” or “flowers” of the tree. In the first order of construction the fractal, we build three new cone frustums connected with a face of the original cone frustum. In this example, we have solid representations in orders from 0 to 6. 
 <br>
<hr>
<p class="topop"><a href="#p1" class="topo">back to top</a></p>
<h4>21. Pentagonal fractal tree with triakis icosahedrons</h4>
<a href="vr/Tree2a.htm" target="_blank" title="3D model" class="fotoA"><img src="ar/21A.png" class="foto" alt="Pentagonal fractal tree with triakis icosahedrons"></a>
 <br>Applying the principle of repetitions with cone frustum, we obtain a fractal tree. In this example, we added triakis icosahedrons as the “fruits” or “flowers” of the tree. In the first order of construction the fractal, we build three new cone frustums connected with a face of the original cone frustum. In this example, we have solid representations in orders from 0 to 5. 
 <br>
<hr>
<h4>22. Triangular fractal tree with pentagonal hexecontahedrons</h4>
<a href="vr/Tree3.htm" target="_blank" title="3D model" class="fotoA"><img src="ar/22A.png" class="foto" alt="Triangular fractal tree with pentagonal hexecontahedrons"></a>
 <br>Applying the principle of repetitions with cone frustum, we obtain a fractal tree. In this example, we added pentagonal hexecontahedrons as the “fruits” or “flowers” of the tree. In the first order of construction the fractal, we build three new cone frustums connected with a face of the original cone frustum. In this example, we have solid representations in orders from 0 to 6. 
 <br>
<hr>
<h4>23. Pentagonal fractal tree with pentagonal hexecontahedrons</h4>
<a href="vr/Tree3a.htm" target="_blank" title="3D model" class="fotoA"><img src="ar/23A.png" class="foto" alt="Pentagonal fractal tree with pentagonal hexecontahedrons"></a>
 <br>Applying the principle of repetitions with cone frustum, we obtain a fractal tree. In this example, we added pentagonal hexecontahedrons as the “fruits” or “flowers” of the tree. In the first order of construction the fractal, we build three new cone frustums connected with a face of the original cone frustum. In this example, we have solid representations in orders from 0 to 5. 
 <br>
<hr>
<h4>24. Triangular fractal tree with pentagonal icositetrahedrons</h4>
<a href="vr/Tree4.htm" target="_blank" title="3D model" class="fotoA"><img src="ar/24A.png" class="foto" alt="Triangular fractal tree with pentagonal icositetrahedrons"></a>
 <br>Applying the principle of repetitions with cone frustum, we obtain a fractal tree. In this example, we added pentagonal icositetrahedrons as the “fruits” or “flowers” of the tree. In the first order of construction the fractal, we build three new cone frustums connected with a face of the original cone frustum. In this example, we have solid representations in orders from 0 to 6. 
 <br>
<hr>
<h4>25. Pentagonal fractal tree with pentagonal icositetrahedrons</h4>
<a href="vr/Tree4a.htm" target="_blank" title="3D model" class="fotoA"><img src="ar/25A.png" class="foto" alt="Pentagonal fractal tree with pentagonal icositetrahedrons"></a>
 <br>Applying the principle of repetitions with cone frustum, we obtain a fractal tree. In this example, we added pentagonal icositetrahedrons as the “fruits” or “flowers” of the tree. In the first order of construction the fractal, we build three new cone frustums connected with a face of the original cone frustum. In this example, we have solid representations in orders from 0 to 5. 
 <br>
<hr>
<h4>26. Triakis icosahedron</h4>
<a href="vr/TriakisIcosahedron.htm" target="_blank" title="3D model" class="fotoA"><img src="ar/26A.png" class="foto" alt="Triakis Icosahedron fractal"></a>
 <br>Applying the construction principle of the Koch curve to faces of the triakis icosahedron, we obtain a triakis icosahedron fractal. In the first order of fractal construction, we construct a new solid at 20 vertices of the original polyhedron. In this example, we have representations of the solid in orders 0, 1, 2 and 3.
 <table margin="auto">
	<tr>
		<th>order</th>
		<th>polyhedra</th>
		<th>faces</th>
		<th>edges</th>
		<th>vertices</th>
	</tr>
	<tr>
		<td>0</td>
		<td>1</td>
		<td>60</td>
		<td>90</td>
		<td>32</td>
	</tr>
	<tr>
		<td>1</td>
		<td>21</td>
		<td>1260</td>
		<td>1890</td>
		<td>672</td>
	</tr>
	<tr>
		<td>2</td>
		<td>441</td>
		<td>26460</td>
		<td>39690</td>
		<td>14112</td>
	</tr>
	<tr>
		<td>3</td>
		<td>9261</td>
		<td>555660</td>
		<td>833490</td>
		<td>296352</td>
	</tr>
 </table>
 <br>
<hr>
<h4>27. Triakis octahedron</h4>
<a href="vr/TriakisOctahedron.htm" target="_blank" title="3D model" class="fotoA"><img src="ar/27A.png" class="foto" alt="Triakis octahedron fractal"></a>
 <br>Applying the construction principle of the Sierpinski curve to faces of the triakis octahedron, we obtain a triakis octahedron fractal. In the first order of fractal construction, we construct a new solid at 6 vertices of the original polyhedron. In this example, we have representations of the solid in orders 0, 1, 2, 3 and 4.
 <table margin="auto">
	<tr>
		<th>order</th>
		<th>polyhedra</th>
		<th>faces</th>
		<th>edges</th>
		<th>vertices</th>
	</tr>
	<tr>
		<td>0</td>
		<td>1</td>
		<td>24</td>
		<td>36</td>
		<td>14</td>
	</tr>
	<tr>
		<td>1</td>
		<td>6</td>
		<td>144</td>
		<td>216</td>
		<td>84</td>
	</tr>
	<tr>
		<td>2</td>
		<td>36</td>
		<td>864</td>
		<td>1296</td>
		<td>504</td>
	</tr>
	<tr>
		<td>3</td>
		<td>216</td>
		<td>5184</td>
		<td>7776</td>
		<td>3024</td>
	</tr>
	<tr>
		<td>4</td>
		<td>1296</td>
		<td>31104</td>
		<td>46656</td>
		<td>18144</td>
	</tr>
 </table>
 <br>
<hr>
<h4>28. Triakis tetrahedron</h4>
<a href="vr/TriakisTetrahedron.htm" target="_blank" title="3D model" class="fotoA"><img src="ar/28A.png" class="foto" alt="Triakis tetrahedron fractal"></a>
 <br>Applying the construction principle of the Sierpinski curve to faces of the triakis tetrahedron, we obtain a triakis tetrahedron fractal. In the first order of fractal construction, we construct a new solid at 4 vertices of the original polyhedron. In this example, we have representations of the solid in orders 0, 1, 2, 3 and 4.
 <table margin="auto">
	<tr>
		<th>order</th>
		<th>polyhedra</th>
		<th>faces</th>
		<th>edges</th>
		<th>vertices</th>
	</tr>
	<tr>
		<td>0</td>
		<td>1</td>
		<td>12</td>
		<td>18</td>
		<td>8</td>
	</tr>
	<tr>
		<td>1</td>
		<td>4</td>
		<td>48</td>
		<td>72</td>
		<td>32</td>
	</tr>
	<tr>
		<td>2</td>
		<td>16</td>
		<td>192</td>
		<td>288</td>
		<td>128</td>
	</tr>
	<tr>
		<td>3</td>
		<td>64</td>
		<td>768</td>
		<td>1152</td>
		<td>512</td>
	</tr>
	<tr>
		<td>4</td>
		<td>256</td>
		<td>3072</td>
		<td>4608</td>
		<td>2048</td>
	</tr>
 </table>
 <br>
<hr>
<h4>29. Archimedean truncated icosahedron</h4>
<a href="vr/TruncatedIcosahedron2.htm" target="_blank" title="3D model" class="fotoA"><img src="ar/29A.png" class="foto" alt="truncated icosahedron fractal"></a>
 <br>Applying the construction principle of the Koch curve to faces of the truncated icosahedron, we obtain a truncated icosahedron fractal. In the first order of fractal construction, we construct a new solid at 20 vertices of the original polyhedron. In this example, we have representations of the solid in orders 0, 1, 2 and 3.
 <table margin="auto">
	<tr>
		<th>order</th>
		<th>polyhedra</th>
		<th>faces</th>
		<th>edges</th>
		<th>vertices</th>
	</tr>
	<tr>
		<td>0</td>
		<td>1</td>
		<td>32</td>
		<td>90</td>
		<td>60</td>
	</tr>
	<tr>
		<td>1</td>
		<td>21</td>
		<td>672</td>
		<td>1890</td>
		<td>1260</td>
	</tr>
	<tr>
		<td>2</td>
		<td>441</td>
		<td>14112</td>
		<td>39690</td>
		<td>26460</td>
	</tr>
	<tr>
		<td>3</td>
		<td>9261</td>
		<td>296352</td>
		<td>833490</td>
		<td>555660</td>
	</tr>
 </table>
 <br>
<hr>
<h4>30. Archimedean truncated icosidodecahedron</h4>
<a href="vr/TruncatedIcosidodecahedron2.htm" target="_blank" title="3D model" class="fotoA"><img src="ar/30A.png" class="foto" alt="truncated icosidodecahedron fractal"></a>
 <br>Applying the construction principle of the Koch curve to faces of the truncated icosidodecahedron, we obtain a truncated icosidodecahedron fractal. In the first order of fractal construction, we construct a new solid at 20 vertices of the original polyhedron. In this example, we have representations of the solid in orders 0, 1, 2 and 3.
 <table margin="auto">
	<tr>
		<th>order</th>
		<th>polyhedra</th>
		<th>faces</th>
		<th>edges</th>
		<th>vertices</th>
	</tr>
	<tr>
		<td>0</td>
		<td>1</td>
		<td>62</td>
		<td>180</td>
		<td>120</td>
	</tr>
	<tr>
		<td>1</td>
		<td>21</td>
		<td>1302</td>
		<td>3780</td>
		<td>2520</td>
	</tr>
	<tr>
		<td>2</td>
		<td>441</td>
		<td>27342</td>
		<td>79380</td>
		<td>52920</td>
	</tr>
	<tr>
		<td>3</td>
		<td>9261</td>
		<td>574182</td>
		<td>1666980</td>
		<td>1111320</td>
	</tr>
 </table>
 <br>
<hr>
<p class="topop"><a href="#p1" class="topo">back to top</a></p>

<br><a rel="license" href="http://creativecommons.org/licenses/by-nc-nd/4.0/"><img alt="Licença Creative Commons" style="border-width:0" src="https://i.creativecommons.org/l/by-nc-nd/4.0/88x31.png" loading="lazy"/></a><br /><span xmlns:dct="http://purl.org/dc/terms/" property="dct:title">Catalan fractals: visualization with Virtual Reality</span> by <a xmlns:cc="http://creativecommons.org/ns#" href="https://paulohscwb.github.io/polyhedra3/fractal-catalan/" property="cc:attributionName" rel="cc:attributionURL">Paulo Henrique Siqueira</a> is licensed with a license <a rel="license" href="http://creativecommons.org/licenses/by-nc-nd/4.0/">Creative Commons Attribution-NonCommercial-NoDerivatives 4.0 International</a>.

<h4>How to cite this work:</h4> 
<p>Siqueira, P.H., "Catalan fractals: visualization with Virtual Reality". Available in: <https://paulohscwb.github.io/polyhedra3/fractal-catalan/>, February 2026.</p>
<!--<a target="_blank" href="https://doi.org/10.5281/zenodo.14502405"><img src="https://zenodo.org/badge/DOI/10.5281/zenodo.14502405.svg" alt="DOI"></a>-->
<br><br><b>References:</b>
<br>Weisstein, Eric W. "Archimedean Solid" From MathWorld-A Wolfram Web Resource. <a href="http://mathworld.wolfram.com/ArchimedeanSolid.html" target="_blank">http://mathworld.wolfram.com/ArchimedeanSolid.html</a>
<br>Weisstein, Eric W. "Catalan Solid" From MathWorld-A Wolfram Web Resource. <a href="https://mathworld.wolfram.com/CatalanSolid.html" target="_blank">https://mathworld.wolfram.com/CatalanSolid.html</a>
<br>McCooey, D. I. "Visual Polyhedra". <a href="http://dmccooey.com/polyhedra/" target="_blank">http://dmccooey.com/polyhedra/</a>
