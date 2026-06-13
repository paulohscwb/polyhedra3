<link rel="stylesheet" href="../scripts/style.css">
<meta charset="utf-8">
<link rel="icon" type="image/png" href="vr/salas/imagens/icone.png">
<h2>Visualization of Polyhedra with Virtual Reality (VR) in A-frame</h2>
 <b>author:</b> Paulo Henrique Siqueira - Universidade Federal do Paraná
 <br><b>contact:</b> <a href="#">paulohscwb@gmail.com</a>
 <br><a href="https://paulohscwb.github.io/polyhedra3/deltahedra/pt-br/">versão em português</a>
 <form style="margin: 0 auto; float:right; text-align:right; width:100%; margin-bottom:15px;">
	<select id="url" onchange="urlHandler(this.value)" style="color:royalblue;">
		<option disabled selected value>More solids:</option>
		<option value="../catalangems/">Catalan gems</option>
		<option value="../dragon-archimedes/">Archimedes and Catalan Dragon Fractals</option>
		<option value="../kites/">Star kites</option>
		<option value="../araucaria/">Araucaria with polyhedrons</option>
		<option value="../dragon-nonconvex/">Dragon fractals of non-convex polyhedra</option>
		<option value="../fractal-catalan/">Catalan fractals</option>
		<option disabled value="../deltahedra/">Non-convex deltahedra</option>
		<!--<option value="../unicorn-platonic/">Plato's Unicorn Fractals</option>
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
  <h2 align="center"><img src="vr/salas/imagens/icone.png" style="margin-bottom:-10px" width="45"> Non-convex deltahedra</h2>
Henry Martyn Cundy identified 17 concave deltahedra (1952), leading to the discovery published by Roger Kaufman (2008) that there are at least 40 examples of this type. Deltahedra are composed only of equilateral triangles, and there are only eight convex deltahedra: tetrahedron, octahedron, icosahedron, triangular dipyramid (Johnson solid J12), pentagonal dipyramid (J13), snub dysphenoid (J84), triaugmented triangular prism (J51), and gyroelongated square dipyramid (J17).
<br>This work shows some non-convex deltahedra modeled for visualization in Virtual Reality.
<p align="center"><a href="#m3d">3D Models</a><span>&nbsp;&nbsp;|&nbsp;&nbsp;</span><a href="../">Home</a></p>
<hr>
 <p align="center"><img src="vr/salas/videos/video1.gif" style="max-width: 85%; border-radius:5px;" loading="lazy" alt="RV de Arquimedes"/></p> 
<hr>
<h3 id="m3d" align="center">3D models</h3>
<!--<iframe width="560" height="315" style="max-width:100%" src="https://www.youtube.com/embed/videoseries?list=PLy0I_lGW8HxU7g9x5hkKKNULwWAdRiCHW" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>-->
<h4>1. Augmented tetrahedron</h4>
<a href="vr/01_Tetraugmented_Tetrahedron.htm" target="_blank" title="3D model" class="fotoA"><img src="ar/1A.png" class="foto" alt="Augmented Tetrahedron"></a>
 <br>This deltahedron is constructed from a regular tetrahedral core, to which tetrahedral "caps" (augmentations) are attached on its four faces.
 <br><b>faces:</b> 12  |  <b>edges:</b> 18  |  <b>vertices:</b> 8
 <br>
<hr>
<h4>2. Gyraugmented tetrahedron</h4>
<a href="vr/02_Tetragyraugmented_Tetrahedron.htm" target="_blank" title="3D model" class="fotoA"><img src="ar/2A.png" class="foto" alt="Gyraugmented Tetrahedron"></a>
 <br>This deltahedron is constructed from a regular tetrahedral core, to which octahedral "caps" (augmentations) are attached on its four faces.
 <br><b>faces:</b> 28  |  <b>edges:</b> 42  |  <b>vertices:</b> 16
 <br>
<hr>
<h4>3. Augmented octahedron</h4>
<a href="vr/03_Octagyraugmented_Octahedron.htm" target="_blank" title="3D model" class="fotoA"><img src="ar/3A.png" class="foto" alt="Augmented Octahedron"></a>
 <br>This deltahedron is constructed from a regular octahedral core, to which octahedral "caps" (augmentations) are attached on its eight faces.
 <br><b>faces:</b> 56  |  <b>edges:</b> 84  |  <b>vertices:</b> 30
 <br>
<hr>
<h4>4. Excavated octahedron</h4>
<a href="vr/04_Octa_excavated_Octahedron.htm" target="_blank" title="3D model" class="fotoA"><img src="ar/4A.png" class="foto" alt="Excavated octahedron"></a>
 <br>This deltahedron is constructed from a regular octahedral core, into which regular tetrahedrons are excavated on its eight faces.
 <br><b>faces:</b> 24  |  <b>edges:</b> 36  |  <b>vertices:</b> 14
 <br>
<hr>
<h4>5. Augmented cube</h4>
<a href="vr/05_Hexaugmented_Cube.htm" target="_blank" title="3D model" class="fotoA"><img src="ar/5A.png" class="foto" alt="Augmented Cube"></a>
 <br>This deltahedron is constructed from a regular cubic core, to which square pyramid-shaped "caps" (augmentations) are attached on its six faces.
 <br><b>faces:</b> 24  |  <b>edges:</b> 36  |  <b>vertices:</b> 14 
 <br>
<hr>
<h4>6. Excavated cube</h4>
<a href="vr/06_Excavated_Cube.htm" target="_blank" title="3D model" class="fotoA"><img src="ar/6A.png" class="foto" alt="Excavated cube"></a>
 <br>This deltahedron is constructed from a regular cubic core, into which square pyramids are excavated on its six faces.
 <br><b>faces:</b> 24  |  <b>edges:</b> 36  |  <b>vertices:</b> 14 
 <br>
<hr>
<h4>7. Excavated dodecahedron</h4>
<a href="vr/07_Dodekexcavated_Dodecahedron.htm" target="_blank" title="3D model" class="fotoA"><img src="ar/7A.png" class="foto" alt="Excavated dodecahedron"></a>
 <br>This deltahedron is constructed from a regular dodecahedral core, into which pentagonal pyramids are excavated on its twelve faces.
 <br><b>faces:</b> 60  |  <b>edges:</b> 90  |  <b>vertices:</b> 32 
 <br>
<hr>
<h4>8. Augmented dodecahedron</h4>
<a href="vr/08_Dodecaugmented_Dodecahedron.htm" target="_blank" title="3D model" class="fotoA"><img src="ar/8A.png" class="foto" alt="Augmented dodecahedron"></a>
 <br>This deltahedron is constructed from a regular dodecahedral core, to which pentagonal pyramid-shaped "caps" (augmentations) are attached on its twelve faces.
 <br><b>faces:</b> 60  |  <b>edges:</b> 90  |  <b>vertices:</b> 32 
 <br>
<hr>
<h4>9. Augmented snub dodecahedron</h4>
<a href="vr/09_Dodecaugmented_Snub_Icosidodecahedron.htm" target="_blank" title="3D model" class="fotoA"><img src="ar/9A.png" class="foto" alt="Augmented snub dodecahedron"></a>
 <br>This deltahedron is constructed from a regular snub dodecahedral core, to which pentagonal pyramid-shaped "caps" (augmentations) are attached on its twelve pentagonal faces.
 <br><b>faces:</b> 140  |  <b>edges:</b> 210  |  <b>vertices:</b> 72 
 <br>
<hr>
<h4>10. Excavated snub dodecahedron</h4>
<a href="vr/10_Dodekexcavated_Snub_Icosidodecahedron.htm" target="_blank" title="3D model" class="fotoA"><img src="ar/10A.png" class="foto" alt="Excavated snub dodecahedron"></a>
 <br>This deltahedron is constructed from a regular snub dodecahedral core, to which pentagonal pyramids are excavated on its twelve pentagonal faces.
 <br><b>faces:</b> 140  |  <b>edges:</b> 210  |  <b>vertices:</b> 72 
 <br>
<hr>
<p class="topop"><a href="#p1" class="topo">back to top</a></p>
<h4>11. Augmented rhombicuboctahedron</h4>
<a href="vr/11_RhombicuboctahedronAugmented.htm" target="_blank" title="3D model" class="fotoA"><img src="ar/11A.png" class="foto" alt="Augmented rhombicuboctahedron"></a>
 <br>This deltahedron is constructed from a rhombicuboctahedron core, to which square pyramid-shaped "caps" (augmentations) are attached on its square faces.
 <br><b>faces:</b> 80  |  <b>edges:</b> 120  |  <b>vertices:</b> 42 
 <br>
<hr>
<h4>12. Excavated rhombicuboctahedron </h4>
<a href="vr/12_RhombicuboctahedronExcaveted.htm" target="_blank" title="3D model" class="fotoA"><img src="ar/12A.png" class="foto" alt="Excavated rhombicuboctahedron"></a>
 <br>This deltahedron is constructed from a rhombicuboctahedron core, to which square pyramids are excavated on its square faces.
 <br><b>faces:</b> 80  |  <b>edges:</b> 120  |  <b>vertices:</b> 42 
 <br>
<hr>
<h4>13. Excavated icosidodecahedron</h4>
<a href="vr/13_Dodekexcavated_Icosidodecahedron.htm" target="_blank" title="3D model" class="fotoA"><img src="ar/13A.png" class="foto" alt="Excavated icosidodecahedron"></a>
 <br>This deltahedron is constructed from a icosidodecahedron core, to which pentagonal pyramids are excavated on its pentagonal faces.
 <br><b>faces:</b> 80  |  <b>edges:</b> 120  |  <b>vertices:</b> 42
 <br>
<hr>
<h4>14. Augmented snub cube</h4>
<a href="vr/14_Hexaugmented_Snub_Cube.htm" target="_blank" title="3D model" class="fotoA"><img src="ar/14A.png" class="foto" alt="Augmented snub cube"></a>
 <br>This deltahedron is constructed from a snub cube core, to which square pyramid-shaped "caps" (augmentations) are attached on its square faces.
 <br><b>faces:</b> 56  |  <b>edges:</b> 84  |  <b>vertices:</b> 30
 <br>
<hr>
<h4>15. Excavated snub cube</h4>
<a href="vr/15_Hexexcavated_Snub_Cube.htm" target="_blank" title="3D model" class="fotoA"><img src="ar/15A.png" class="foto" alt="Excavated snub cube"></a>
 <br>This deltahedron is constructed from a snub cube core, to which square pyramids are excavated on its square faces.
 <br><b>faces:</b> 56  |  <b>edges:</b> 84  |  <b>vertices:</b> 30
 <br>
<hr>
<h4>16. Excavated small snub icosicosidodecahedron</h4>
<a href="vr/16_Dodekexcavated_Seside.htm" target="_blank" title="3D model" class="fotoA"><img src="ar/16A.png" class="foto" alt="Excavated small snub icosicosidodecahedron"></a>
 <br>This deltahedron is constructed from a small snub icosicosidodecahedron core, to which pentagrammic pyramids are excavated on its pentagrammic faces.
 <br><b>faces:</b> 160  |  <b>edges:</b> 240  |  <b>vertices:</b> 82
 <br>
<hr>
<h4>17. Augmented small snub icosicosidodecahedron</h4>
<a href="vr/17_Dodecaugmented_Seside.htm" target="_blank" title="3D model" class="fotoA"><img src="ar/17A.png" class="foto" alt="Augmented small snub icosicosidodecahedron"></a>
 <br>This deltahedron is constructed from a small snub icosicosidodecahedron core, to which pentagrammic pyramid-shaped "caps" (augmentations) are attached on its pentagrammic faces.
 <br><b>faces:</b> 160  |  <b>edges:</b> 240  |  <b>vertices:</b> 82
 <br>
<hr>
<h4>18. Augmented great icosahedron</h4>
<a href="vr/18_Tetraugmented_Gike.htm" target="_blank" title="3D model" class="fotoA"><img src="ar/18A.png" class="foto" alt="Tetraugmented great icosahedron"></a>
 <br>This deltahedron is constructed from a great icosahedron core, to which regular tetrahedron-shaped "caps" (augmentations) are attached on four faces.
 <br><b>faces:</b> 28  |  <b>edges:</b> 42  |  <b>vertices:</b> 16
 <br>
<hr>
<h4>19. Excavated great stellated dodecahedron</h4>
<a href="vr/19_Dodekexcavated_Gissid.htm" target="_blank" title="3D model" class="fotoA"><img src="ar/19A.png" class="foto" alt="Excavated great stellated dodecahedron"></a>
 <br>This deltahedron is constructed from a great stellated dodecahedron core, to which pentagrammic pyramids are excavated on its pentagrammic faces.
 <br><b>faces:</b> 60  |  <b>edges:</b> 90  |  <b>vertices:</b> 32
 <br>
<hr>
<h4>20. Excavated great icosahedron</h4>
<a href="vr/20_Icosagyrexcavated_Gike.htm" target="_blank" title="3D model" class="fotoA"><img src="ar/20A.png" class="foto" alt="Excavated great icosahedron"></a>
 <br>This deltahedron is constructed from a great icosahedron core, to which regular octahedra are excavated on its faces.
 <br><b>faces:</b> 140  |  <b>edges:</b> 210  |  <b>vertices:</b> 72
 <br>
<hr>
<p class="topop"><a href="#p1" class="topo">back to top</a></p>
<h4>21. Excavated great ditrigonal icosidodecahedron</h4>
<a href="vr/21_Dodekexcavated_Gidtid.htm" target="_blank" title="3D model" class="fotoA"><img src="ar/21A.png" class="foto" alt="Excavated great ditrigonal icosidodecahedron"></a>
 <br>This deltahedron is constructed from a great ditrigonal icosidodecahedron core, to which pentagrammic pyramids are excavated on its pentagrammic faces.
 <br><b>faces:</b> 80  |  <b>edges:</b> 120  |  <b>vertices:</b> 42
 <br>
<hr>
<h4>22. Augmented stellated truncated hexahedron</h4>
<a href="vr/22_Octaugmented_Quith.htm" target="_blank" title="3D model" class="fotoA"><img src="ar/22A.png" class="foto" alt="Augmented stellated truncated hexahedron"></a>
 <br>This deltahedron is constructed from a stellated truncated hexahedron core, to which octagrammic pyramid-shaped "caps" (augmentations) are attached on its octagrammic faces.
 <br><b>faces:</b> 56  |  <b>edges:</b> 84  |  <b>vertices:</b> 30
 <br>
<hr>
<h4>23. Excavated stellated truncated hexahedron</h4>
<a href="vr/23_Octaexcavated_Quith.htm" target="_blank" title="3D model" class="fotoA"><img src="ar/23A.png" class="foto" alt="Excavated stellated truncated hexahedron"></a>
 <br>This deltahedron is constructed from a stellated truncated hexahedron core, to which octagrammic pyramids are excavated on its octagrammic faces.
 <br><b>faces:</b> 56  |  <b>edges:</b> 84  |  <b>vertices:</b> 30
 <br>
<hr>
<h4>24. Augmented small ditrigonal icosidodecahedron</h4>
<a href="vr/24_Dodecaugmented_Sidtid.htm" target="_blank" title="3D model" class="fotoA"><img src="ar/24A.png" class="foto" alt="Augmented small ditrigonal icosidodecahedron"></a>
 <br>This deltahedron is constructed from a small ditrigonal icosidodecahedron core, to which pentagrammic pyramid-shaped "caps" (augmentations) are attached on its pentagrammic faces.
 <br><b>faces:</b> 80  |  <b>edges:</b> 120  |  <b>vertices:</b> 42
 <br>
<hr>
<h4>25. Excavated small ditrigonal icosidodecahedron</h4>
<a href="vr/25_Dodekexcavated_Sidtid.htm" target="_blank" title="3D model" class="fotoA"><img src="ar/25A.png" class="foto" alt="Excavated small ditrigonal icosidodecahedron"></a>
 <br>This deltahedron is constructed from a small ditrigonal icosidodecahedron core, to which pentagrammic pyramids are excavated on its pentagrammic faces.
 <br><b>faces:</b> 80  |  <b>edges:</b> 120  |  <b>vertices:</b> 42
 <br>
<hr>
<h4>26. Diexcavated octahedron</h4>
<a href="vr/26_Diexcavated_Octahedron.htm" target="_blank" title="3D model" class="fotoA"><img src="ar/26A.png" class="foto" alt="Diexcavated octahedron"></a>
 <br>This deltahedron is constructed from an octahedron core, to which tetrahedra are excavated on two parallel faces.
 <br><b>faces:</b> 12  |  <b>edges:</b> 18  |  <b>vertices:</b> 8
 <br>
<hr>
<h4>27. Diexcavated square antiprism</h4>
<a href="vr/27_Diexcavated_Square_Antiprism.htm" target="_blank" title="3D model" class="fotoA"><img src="ar/27A.png" class="foto" alt="Diexcavated square antiprism"></a>
 <br>This deltahedron is constructed from a square antiprism core, to which square pyramids are excavated on its square faces.
 <br><b>faces:</b> 16  |  <b>edges:</b> 24  |  <b>vertices:</b> 10
 <br>
<hr>
<h4>28. Diexcavated pentagonal antiprism</h4>
<a href="vr/28_Diexcavated_Pentagonal_Antiprism.htm" target="_blank" title="3D model" class="fotoA"><img src="ar/28A.png" class="foto" alt="Diexcavated pentagonal antiprism"></a>
 <br>This deltahedron is constructed from a pentagonal antiprism core, to which pentagonal pyramids are excavated on its pentagonal faces.
 <br><b>faces:</b> 20  |  <b>edges:</b> 30  |  <b>vertices:</b> 12
 <br>
<hr>
<h4>29. Tetrambiated icosahedron</h4>
<a href="vr/29_Tetrambiated_Icosahedron.htm" target="_blank" title="3D model" class="fotoA"><img src="ar/29A.png" class="foto" alt="Tetrambiated Icosahedron"></a>
 <br>This polyhedron is formed by four sets of four triangles arranged tetrahedrally in the icosahedron, combined symmetrically with a set of ten equilateral triangles, generating a Cundy deltahedron with 44 faces.
 <br><b>faces:</b> 44  |  <b>edges:</b> 66  |  <b>vertices:</b> 24
 <br>
<hr>
<h4>30. Hexaspheniated icosahedron</h4>
<a href="vr/30_Hexaspheniated_Icosahedron.htm" target="_blank" title="3D model" class="fotoA"><img src="ar/30A.png" class="foto" alt="Hexaspheniated icosahedron"></a>
 <br>This polyhedron is formed by the combination of sphenoid structures (tetrahedral wedges), joined to a basic icosahedral structure.
 <br><b>faces:</b> 44  |  <b>edges:</b> 66  |  <b>vertices:</b> 24
 <br>
<hr>
<p class="topop"><a href="#p1" class="topo">back to top</a></p>
<h4>31. Augmented pentagrammic antiprism</h4>
<a href="vr/33_PentagrammicAntiprismAugmented.htm" target="_blank" title="3D model" class="fotoA"><img src="ar/31A.png" class="foto" alt="Augmented Pentagrammic antiprism"></a>
 <br>This deltahedron is constructed from a pentagrammic antiprism core, to which pentagrammic pyramid-shaped "caps" (augmentations) are attached on its pentagrammic faces.
 <br><b>faces:</b> 20  |  <b>edges:</b> 30  |  <b>vertices:</b> 12
 <br>
<hr>
<h4>32. Excavated Pentagrammic antiprism</h4>
<a href="vr/34_PentagrammicAntiprismExcavated.htm" target="_blank" title="3D model" class="fotoA"><img src="ar/32A.png" class="foto" alt="excavated Pentagrammic antiprism"></a>
 <br>This deltahedron is constructed from a pentagrammic antiprism core, to which pentagrammic pyramids are excavated on its pentagrammic faces.
 <br><b>faces:</b> 20  |  <b>edges:</b> 30  |  <b>vertices:</b> 12
 <br>
<hr>
<h4>33. Augmented Pentagrammic crossed antiprism</h4>
<a href="vr/31_PentagrammicCrossedAntiprismAugmented.htm" target="_blank" title="3D model" class="fotoA"><img src="ar/33A.png" class="foto" alt="Augmented Pentagrammic crossed antiprism"></a>
 <br>This deltahedron is constructed from a pentagrammic crossed antiprism core, to which pentagrammic pyramid-shaped "caps" (augmentations) are attached on its pentagrammic faces.
 <br><b>faces:</b> 20  |  <b>edges:</b> 30  |  <b>vertices:</b> 12
 <br>
<hr>
<h4>34. Excavated Pentagrammic crossed antiprism</h4>
<a href="vr/32_PentagrammicCrossedAntiprismExcavated.htm" target="_blank" title="3D model" class="fotoA"><img src="ar/34A.png" class="foto" alt="Excavated Pentagrammic crossed antiprism"></a>
 <br>This deltahedron is constructed from a pentagrammic crossed antiprism core, to which pentagrammic pyramids are excavated on its pentagrammic faces.
 <br><b>faces:</b> 20  |  <b>edges:</b> 30  |  <b>vertices:</b> 12
 <br>
<hr>
<h4>35. Augmented great icosidodecahedron</h4>
<a href="vr/35_Dodekaugmented_Gid.htm" target="_blank" title="3D model" class="fotoA"><img src="ar/35A.png" class="foto" alt="Augmented great icosidodecahedron"></a>
 <br>This deltahedron is constructed from a great icosidodecahedron core, to which pentagrammic pyramid-shaped "caps" (augmentations) are attached on its pentagrammic faces.
 <br><b>faces:</b> 80  |  <b>edges:</b> 120  |  <b>vertices:</b> 42
 <br>
<hr>
<h4>36. Excavated great icosidodecahedron</h4>
<a href="vr/36_Dodekexcavated_Gid.htm" target="_blank" title="3D model" class="fotoA"><img src="ar/36A.png" class="foto" alt="Excavated great icosidodecahedron"></a>
 <br>This deltahedron is constructed from a great icosidodecahedron core, to which pentagrammic pyramids are excavated on its pentagrammic faces.
 <br><b>faces:</b> 80  |  <b>edges:</b> 120  |  <b>vertices:</b> 42
 <br>
<hr>
<h4>37. Excavated great stellated truncated dodecahedron</h4>
<a href="vr/37_Dodekexcavated_Quitgissid.htm" target="_blank" title="3D model" class="fotoA"><img src="ar/37A.png" class="foto" alt="Excavated great stellated truncated dodecahedron"></a>
 <br>This deltahedron is constructed from a great stellated truncated dodecahedron core, to which pentagrammic pyramids are excavated on its pentagrammic faces.
 <br><b>faces:</b> 140  |  <b>edges:</b> 210  |  <b>vertices:</b> 72
 <br>
<hr>
<h4>38. Augmented great stellated truncated dodecahedron</h4>
<a href="vr/38_Dodecaugmented_Quitgissid.htm" target="_blank" title="3D model" class="fotoA"><img src="ar/38A.png" class="foto" alt="Augmented great stellated truncated dodecahedron"></a>
 <br>This deltahedron is constructed from a great stellated truncated dodecahedron core, to which pentagrammic pyramid-shaped "caps" (augmentations) are attached on its pentagrammic faces.
 <br><b>faces:</b> 140  |  <b>edges:</b> 210  |  <b>vertices:</b> 72
 <br>
<hr>
<h4>39. Excavated great snub icosidodecahedron</h4>
<a href="vr/39_Dodekexcavated_Gisid.htm" target="_blank" title="3D model" class="fotoA"><img src="ar/39A.png" class="foto" alt="Excavated great snub icosidodecahedron"></a>
 <br>This deltahedron is constructed from a great snub icosidodecahedron core, to which pentagrammic pyramids are excavated on its pentagrammic faces.
 <br><b>faces:</b> 140  |  <b>edges:</b> 210  |  <b>vertices:</b> 72
 <br>
<hr>
<h4>40. Augmented great snub icosidodecahedron</h4>
<a href="vr/40_Dodecaugmented_Gisid.htm" target="_blank" title="3D model" class="fotoA"><img src="ar/40A.png" class="foto" alt="Augmented great snub icosidodecahedron"></a>
 <br>This deltahedron is constructed from a great snub icosidodecahedron core, to which pentagrammic pyramid-shaped "caps" (augmentations) are attached on its pentagrammic faces.
 <br><b>faces:</b> 140  |  <b>edges:</b> 210  |  <b>vertices:</b> 72
 <br>
<hr>
<p class="topop"><a href="#p1" class="topo">back to top</a></p>
<h4>41. Augmented great snub inverted icosidodecahedron</h4>
<a href="vr/41_Dodecaugmented_Gosid.htm" target="_blank" title="3D model" class="fotoA"><img src="ar/41A.png" class="foto" alt="Augmented great snub inverted icosidodecahedron"></a>
 <br>This deltahedron is constructed from a great snub inverted icosidodecahedron core, to which pentagrammic pyramid-shaped "caps" (augmentations) are attached on its pentagrammic faces.
 <br><b>faces:</b> 140  |  <b>edges:</b> 210  |  <b>vertices:</b> 72
 <br>
<hr>
<h4>42. Excavated great snub inverted icosidodecahedron</h4>
<a href="vr/42_Dodekexcavated_Gosid.htm" target="_blank" title="3D model" class="fotoA"><img src="ar/42A.png" class="foto" alt="Excavated great snub inverted icosidodecahedron"></a>
 <br>This deltahedron is constructed from a great snub inverted icosidodecahedron core, to which pentagrammic pyramids are excavated on its pentagrammic faces.
 <br><b>faces:</b> 140  |  <b>edges:</b> 210  |  <b>vertices:</b> 72
 <br>
<hr>
<h4>43. Excavated great retrosnub icosidodecahedron</h4>
<a href="vr/43_Dodekexcavated_Girsid.htm" target="_blank" title="3D model" class="fotoA"><img src="ar/43A.png" class="foto" alt="Excavated great retrosnub icosidodecahedron"></a>
 <br>This deltahedron is constructed from a great retrosnub icosidodecahedron core, to which pentagrammic pyramids are excavated on its pentagrammic faces.
 <br><b>faces:</b> 140  |  <b>edges:</b> 210  |  <b>vertices:</b> 72
 <br>
<hr>
<h4>44. Augmented great retrosnub icosidodecahedron</h4>
<a href="vr/44_Dodecaugmented_Girsid.htm" target="_blank" title="3D model" class="fotoA"><img src="ar/44A.png" class="foto" alt="Augmented great retrosnub icosidodecahedron"></a>
 <br>This deltahedron is constructed from a great retrosnub icosidodecahedron core, to which pentagrammic pyramid-shaped "caps" (augmentations) are attached on its pentagrammic faces.
 <br><b>faces:</b> 140  |  <b>edges:</b> 210  |  <b>vertices:</b> 72
 <br>
<hr>
<h4>45. Augmented small retrosnub icosicosidodecahedron</h4>
<a href="vr/45_Dodecaugmented_Sirsid.htm" target="_blank" title="3D model" class="fotoA"><img src="ar/45A.png" class="foto" alt="Augmented small retrosnub icosicosidodecahedron"></a>
 <br>This deltahedron is constructed from a small retrosnub icosicosidodecahedron core, to which pentagrammic pyramid-shaped "caps" (augmentations) are attached on its pentagrammic faces.
 <br><b>faces:</b> 160  |  <b>edges:</b> 240  |  <b>vertices:</b> 82
 <br>
<hr>
<h4>46. Excavated small retrosnub icosicosidodecahedron</h4>
<a href="vr/46_Dodekexcavated_Sirsid.htm" target="_blank" title="3D model" class="fotoA"><img src="ar/46A.png" class="foto" alt="Excavated small retrosnub icosicosidodecahedron"></a>
 <br>This deltahedron is constructed from a small retrosnub icosicosidodecahedron core, to which pentagrammic pyramids are excavated on its pentagrammic faces.
 <br><b>faces:</b> 160  |  <b>edges:</b> 240  |  <b>vertices:</b> 82
 <br>
<hr>
<h4>47. Excavated great snub dodecicosidodecahedron</h4>
<a href="vr/47_Dodekexcavated_Gsd.htm" target="_blank" title="3D model" class="fotoA"><img src="ar/47A.png" class="foto" alt="Augmented great snub dodecicosidodecahedron"></a>
 <br>This deltahedron is constructed from a great snub dodecicosidodecahedron core, to which pentagrammic pyramids are excavated on its pentagrammic faces.
 <br><b>faces:</b> 200  |  <b>edges:</b> 300  |  <b>vertices:</b> 84
 <br>
<hr>
<h4>48. Augmented great snub dodecicosidodecahedron</h4>
<a href="vr/48_Dodekaugmented_Gsd.htm" target="_blank" title="3D model" class="fotoA"><img src="ar/48A.png" class="foto" alt="Excavated great snub dodecicosidodecahedron"></a>
 <br>This deltahedron is constructed from a great snub dodecicosidodecahedron core, to which pentagrammic pyramid-shaped "caps" (augmentations) are attached on its pentagrammic faces.
 <br><b>faces:</b> 200  |  <b>edges:</b> 300  |  <b>vertices:</b> 84
 <br>
<hr>
<h4>49. Augmented snub dodecadodecahedron</h4>
<a href="vr/49_Dodekaugmented_Sd.htm" target="_blank" title="3D model" class="fotoA"><img src="ar/49A.png" class="foto" alt="Augmented snub dodecadodecahedron"></a>
 <br>This deltahedron is constructed from a snub dodecadodecahedron core, to which pentagrammic and pentagonal pyramid-shaped "caps" (augmentations) are attached on its pentagrammic and pentagonal faces.
 <br><b>faces:</b> 140  |  <b>edges:</b> 210  |  <b>vertices:</b> 84
 <br>
<hr>
<h4>50. Excavated snub dodecadodecahedron</h4>
<a href="vr/50_Dodekexcavated_Sd.htm" target="_blank" title="3D model" class="fotoA"><img src="ar/50A.png" class="foto" alt="Excavated snub dodecadodecahedron"></a>
 <br>This deltahedron is constructed from a snub dodecadodecahedron core, to which pentagrammic and pentagonal pyramids are excavated on its pentagrammic and pentagonal faces.
 <br><b>faces:</b> 140  |  <b>edges:</b> 210  |  <b>vertices:</b> 84
 <br>
<hr>
<p class="topop"><a href="#p1" class="topo">back to top</a></p>
<h4>51. Excavated and augmented snub dodecadodecahedron</h4>
<a href="vr/51_Dodekaugmentedexcavated_Sd.htm" target="_blank" title="3D model" class="fotoA"><img src="ar/51A.png" class="foto" alt="Excavated and augmented snub dodecadodecahedron"></a>
 <br>This deltahedron is constructed from a snub dodecadodecahedron core, to which pentagrammic pyramids are excavated on its pentagrammic faces, and pentagonal pyramid-shaped "caps" (augmentations) are attached on its pentagonal faces.
 <br><b>faces:</b> 140  |  <b>edges:</b> 210  |  <b>vertices:</b> 84
 <br>
<hr>
<h4>52. Augmented inverted snub dodecadodecahedron</h4>
<a href="vr/52_Dodekaugmented_Sid.htm" target="_blank" title="3D model" class="fotoA"><img src="ar/52A.png" class="foto" alt="Augmented inverted snub dodecadodecahedron"></a>
 <br>This deltahedron is constructed from a inverted snub dodecadodecahedron core, to which pentagrammic and pentagonal pyramid-shaped "caps" (augmentations) are attached on its pentagrammic and pentagonal faces.
 <br><b>faces:</b> 140  |  <b>edges:</b> 210  |  <b>vertices:</b> 84
 <br>
<hr>
<h4>53. Excavated inverted snub dodecadodecahedron</h4>
<a href="vr/53_Dodekexcavated_Sid.htm" target="_blank" title="3D model" class="fotoA"><img src="ar/53A.png" class="foto" alt="Excavated inverted snub dodecadodecahedron"></a>
 <br>This deltahedron is constructed from a inverted snub dodecadodecahedron core, to which pentagrammic and pentagonal pyramids are excavated on its pentagrammic and pentagonal faces.
 <br><b>faces:</b> 140  |  <b>edges:</b> 210  |  <b>vertices:</b> 84
 <br>
<hr>
<h4>54. Excavated and augmented inverted snub dodecadodecahedron</h4>
<a href="vr/54_Dodekaugmentedexcavated_Sid.htm" target="_blank" title="3D model" class="fotoA"><img src="ar/54A.png" class="foto" alt="Excavated and augmented inverted snub dodecadodecahedron"></a>
 <br>This deltahedron is constructed from a inverted snub dodecadodecahedron core, to which pentagrammic pyramids are excavated on its pentagrammic faces, and pentagonal pyramid-shaped "caps" (augmentations) are attached on its pentagonal faces.
 <br><b>faces:</b> 140  |  <b>edges:</b> 210  |  <b>vertices:</b> 84
 <br>
<hr>
<h4>55. Augmented snub icosidodecadodecahedron</h4>
<a href="vr/57_Dodekaugmented_Sic.htm" target="_blank" title="3D model" class="fotoA"><img src="ar/55A.png" class="foto" alt="Augmented snub icosidodecadodecahedron"></a>
 <br>This deltahedron is constructed from a snub icosidodecadodecahedron core, to which pentagrammic and pentagonal pyramid-shaped "caps" (augmentations) are attached on its pentagrammic and pentagonal faces.
 <br><b>faces:</b> 140  |  <b>edges:</b> 210  |  <b>vertices:</b> 84
 <br>
<hr>
<h4>56. Excavated snub icosidodecadodecahedron</h4>
<a href="vr/55_Dodekexcavated_Sic.htm" target="_blank" title="3D model" class="fotoA"><img src="ar/56A.png" class="foto" alt="Excavated snub icosidodecadodecahedron"></a>
 <br>This deltahedron is constructed from a great snub icosidodecadodecahedron core, to which pentagrammic and pentagonal pyramids are excavated on its pentagrammic and pentagonal faces.
 <br><b>faces:</b> 140  |  <b>edges:</b> 210  |  <b>vertices:</b> 84
 <br>
<hr>
<h4>57. Excavated and augmented snub icosidodecadodecahedron</h4>
<a href="vr/56_Dodekaugmentedexcavated_Sic.htm" target="_blank" title="3D model" class="fotoA"><img src="ar/57A.png" class="foto" alt="Excavated and augmented snub icosidodecadodecahedron"></a>
 <br>This deltahedron is constructed from a great snub icosidodecadodecahedron core, to which pentagrammic pyramids are excavated on its pentagrammic faces, and pentagonal pyramid-shaped "caps" (augmentations) are attached on its pentagonal faces.
 <br><b>faces:</b> 140  |  <b>edges:</b> 210  |  <b>vertices:</b> 84
 <br>
<hr>
<h4>58. Möbius deltahedron</h4>
<a href="https://paulohscwb.github.io/polyhedra/nonconvex/vr/mobius24.htm" target="_blank" title="3D model" class="fotoA"><img src="https://paulohscwb.github.io/polyhedra/nonconvex/ar/119A.png" class="foto" alt="Möbius Deltahedron"></a>
 <br>Möbius deltahedra are simply isomers of the Möbius triangle versions of the tetrahedron, cube and dodecahedron.
 <br><b>faces:</b> 24  |  <b>edges:</b> 36  |  <b>vertices:</b> 14
 <br>
<hr>
<h4>59. Möbius octakis hexahedron</h4>
<a href="https://paulohscwb.github.io/polyhedra/nonconvex/vr/mobius48a.htm" target="_blank" title="3D model" class="fotoA"><img src="https://paulohscwb.github.io/polyhedra/nonconvex/ar/118A.png" class="foto" alt="Möbius octakis hexahedron"></a>
 <br>The octakis hexahedron is a 48-faced Möbius deltahedron derived from the cube and the medial rhombic triacontahedron.
 <br><b>faces:</b> 48  |  <b>edges:</b> 72  |  <b>vertices:</b> 26
 <br>
<hr>
<h4>60. Möbius hexakis octahedron</h4>
<a href="https://paulohscwb.github.io/polyhedra/nonconvex/vr/mobius48b.htm" target="_blank" title="3D model" class="fotoA"><img src="https://paulohscwb.github.io/polyhedra/nonconvex/ar/117A.png" class="foto" alt="Möbius hexakis octahedron"></a>
 <br>The hexakis octahedron is a 48-faced Möbius deltahedron derived from the cube and the medial rhombic triacontahedron.
 <br><b>faces:</b> 48  |  <b>edges:</b> 72  |  <b>vertices:</b> 26
 <br>
<hr>
<p class="topop"><a href="#p1" class="topo">back to top</a></p>
<h4>61. Möbius hexakis icosahedron</h4>
<a href="https://paulohscwb.github.io/polyhedra/nonconvex/vr/mobius120a.htm" target="_blank" title="3D model" class="fotoA"><img src="https://paulohscwb.github.io/polyhedra/nonconvex/ar/116A.png" class="foto" alt="Möbius hexakis icosahedron"></a>
 <br>The hexakis icosahedron is a 120-faced Möbius deltahedron derived from the icosahedron and the great rhombic triacontahedron.
 <br><b>faces:</b> 120  |  <b>edges:</b> 180  |  <b>vertices:</b> 62
 <br>
<hr>
<h4>62. Möbius 10-akis dodecahedron</h4>
<a href="https://paulohscwb.github.io/polyhedra/nonconvex/vr/mobius120b.htm" target="_blank" title="3D model" class="fotoA"><img src="https://paulohscwb.github.io/polyhedra/nonconvex/ar/115A.png" class="foto" alt="Möbius 10-akis dodecahedron"></a>
 <br>The 10-akis dodecahedron is a 120-faced Möbius deltahedron derived from the dodecahedron and the great rhombic triacontahedron.
 <br><b>faces:</b> 120  |  <b>edges:</b> 180  |  <b>vertices:</b> 62
 <br>
<hr>
<p class="topop"><a href="#p1" class="topo">back to top</a></p>

<br><a rel="license" href="http://creativecommons.org/licenses/by-nc-nd/4.0/"><img alt="Licença Creative Commons" style="border-width:0" src="https://i.creativecommons.org/l/by-nc-nd/4.0/88x31.png" loading="lazy"/></a><br /><span xmlns:dct="http://purl.org/dc/terms/" property="dct:title">Non-convex deltahedra: visualization with Virtual Reality</span> by <a xmlns:cc="http://creativecommons.org/ns#" href="https://paulohscwb.github.io/polyhedra3/deltahedra/" property="cc:attributionName" rel="cc:attributionURL">Paulo Henrique Siqueira</a> is licensed with a license <a rel="license" href="http://creativecommons.org/licenses/by-nc-nd/4.0/">Creative Commons Attribution-NonCommercial-NoDerivatives 4.0 International</a>.

<h4>How to cite this work:</h4> 
<p>Siqueira, P.H., "Non-convex deltahedra: visualization with Virtual Reality". Available in: <https://paulohscwb.github.io/polyhedra3/deltahedra/>, June 2026.</p>
<!--<a target="_blank" href="https://doi.org/10.5281/zenodo.14502405"><img src="https://zenodo.org/badge/DOI/10.5281/zenodo.14502405.svg" alt="DOI"></a>-->
<br><br><b>References:</b>
<br>Weisstein, Eric W. "Archimedean Solid" From MathWorld-A Wolfram Web Resource. <a href="http://mathworld.wolfram.com/ArchimedeanSolid.html" target="_blank">http://mathworld.wolfram.com/ArchimedeanSolid.html</a>
<br>McCooey, D. I. "Visual Polyhedra". <a href="http://dmccooey.com/polyhedra/" target="_blank">http://dmccooey.com/polyhedra/</a>
<br>Cundy, H. M. "Deltahedra". Math. Gaz. v. 36, pp. 263-266, 1952
<br>Kaufman, R. "The Cundy Deltahedra". <a href="http://www.interocitors.com/polyhedra/Deltahedra/Cundy" target="_blank">http://www.interocitors.com/polyhedra/Deltahedra/Cundy</a>
