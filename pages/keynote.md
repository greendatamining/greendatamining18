---
layout: page
title: Keynote Speaker
permalink: /keynote/
feature-img: "assets/img/workshop/dublin.jpg"
---
<h1 style="text-align: center">Keynote Speakers</h1>

<hr>
<div>
        <div style="width:20%; float:left">
			<img src="../assets/img/tonellotto.jpg" alt="Nicola Tonellotto" style="width:100%; margin-bottom: 20px; padding-left: 0px">
		</div>
		<div>
            <div class="speaker_name_inkeynote"><a id="nicola"></a>Nicola Tonellotto</div>
            <div class="speaker_aff_inkeynote">National Research Council of Italy (ISTI)</div>
        </div>
    </div>

 <div style="clear:left;">
<div class="keynote_title">Energy Efficiency in Large Scale Information Retrieval Systems</div>

<button class="collapsible">Abstract
	<hr>
	<div class="abstract_context">
	Web search engines perform distributed query processing on computer clusters composed by thousands of computers and hosted in large data centers. While data center facilities enable large-scale online services, they also raise economical and environmental concerns. Therefore, it is important to reduce the energy expenditure of data centers, as well as to reduce carbon dioxide emissions and the negative impact of the data centers on the environment.
	</div>
</button>
<div class="tocollapse">
  A large part of the energy consumption of a data center could be accounted to inefficiencies in its cooling and power supply systems. However, search companies already adopt state-of-the art techniques to reduce the energy wastage of such systems, leaving little room for more improvements in those areas. Therefore, new approaches are necessary to mitigate the environmental impact and the energy expenditure of Web search engines. <br />
  <br />
  In this talk we will address the reduction of the energy consumption of computing resources to mitigate the energy expenditure and carbon footprint of a IR system. In particular, reducing the energy consumption of CPUs represents an attractive venue for Web search engines. Currently, CPU cores frequencies are typically managed by operating system components, called frequency governors. We will discuss how to delegate the CPU power management from the OS frequency governors to the query processing application. Such IR system-specific governors can reduce up to 24% a server power consumption, with only limited (but uncontrollable) drawbacks in the quality of search results with respect to a system running at maximum CPU frequency. 
	<br /><br />
  Since users can hardly notice response times that are faster than their expectations we advise that Web search engine should not process queries faster than user expectations and, consequently, we will present the Predictive Energy Saving Online Scheduling (PESOS) algorithm, to select the most appropriate CPU frequency to process a query by its deadline, on a per-core basis. PESOS can reduce the CPU energy consumption of a query processing server from 24% up to 48% when compared to an high performance system running at maximum CPU core frequency. To conclude, we will compare the PESOS performance w.r.t. an industry-level baseline, called PEGASUS, on a realistic simulation of a distributed Web search engine. Our results show that PESOS can reduce the CPU energy consumption of a distributed WSE by up to 18% with respect to PEGASUS, while providing query response times which are in line with user expectations.
  
  </div>

<!-- <button class="collapsible">Bio</button>
<div class="tocollapse">
<p> -->
<br />
<div class="bio">
<span class="bio_title"> Bio </span>
<hr>
<div class="bio_context">
Nicola Tonellotto <a href="http://pomino.isti.cnr.it/~khast/">(http://pomino.isti.cnr.it/~khast/)</a> is a researcher at National Research Council of Italy. He received his Ph.D. from the Information Engineering Department of the University of Pisa in 2008. His main research interests include Cloud computing and Web information retrieval. He published over 50 papers in journals and proceedings of international conferences. He received the Best Paper Award at ACM SIGIR in 2015.
</div>
</div>
<!-- </p>
</div> -->

<br /><br /><br />
<div>
        <div style="width:20%; float:left">
			<img src="../assets/img/elsen.jpg" alt="Erich Elsen" style="width:100%; margin-bottom: 20px; padding-left: 0px">
		</div>
		<div>
            <div class="speaker_name_inkeynote"><a id="erich"></a>Erich Elsen 
  			<!-- <span class="fa-stack fa-lg">
            <i class="fa fa-twitter fa-stack-1x fa-inverse" style="font-size:0.8em; color:#10872F"></i>
        	</span> -->
			</div>
            <div class="speaker_aff_inkeynote">Google Brain</div>
        </div>
    </div>

 <div style="clear:left;">
<div class="keynote_title">Fast and Efficient Auto-Regressive Inference</div>
<br />
<div class="bio">
	<span class="bio_title"> Bio </span>
	<hr>
	<div class="bio_context">
		Erich Elsen is a Research Scientist at Google Brain where he collaborates with the Magenta team and DeepMind.  He is generally interested in auto-regressive models, sparse neural networks, optimization, generative models (especially of music) and hardware.  Recently he combined those interests to enable extremely efficient WaveNet quality Text-to-Speech with sparse WaveRNNs.  He also created the world's best piano transcription model Onsets and Frames.  Prior to joining Google he developed the DeepSpeech and DeepSpeech 2 speech transcription systems at Baidu's Silicon Valley AI Lab.  A long time ago he graduated with a PhD in Mechanical Engineering from Stanford in 2009.
	</div>
</div>
</div>



<script>
	var coll = document.getElementsByClassName("collapsible");
	var i;

	for (i = 0; i < coll.length; i++) {
	  coll[i].addEventListener("click", function() {
	    this.classList.toggle("active");
	    var content = this.nextElementSibling;
	    if (content.style.maxHeight){
	      content.style.maxHeight = null;
	    } else {
	      content.style.maxHeight = content.scrollHeight + "px";
	    } 
	  });
	}
</script>



 