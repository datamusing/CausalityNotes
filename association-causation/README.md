# Association != Causation



Machine Learning systems have become exceptionally good at fitting trends/associations in data.  But they are not formulated to answer “What If” questions \(What would have happened if I administered medicine B to this patient who is currently under a  medicine A regimen?\).   Data-driven prediction models are often mistakenly used to draw causal effects, but neither their parameters nor their predictions necessarily have a causal interpretation. Models built for prediction do not guarantee trustable decisions or interventions. This has made 

{% mermaid %} graph LR A\[Hard edge\] --&gt;\|Link text\| B\(Round edge\) B --&gt; C{Decision} C --&gt;\|One\| D\[Result one\] C --&gt;\|Two\| E\[Result two\] {% endmermaid %}





