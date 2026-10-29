# Arctic Tern Migration

Arctic Tern (Sterna paradisaea) are a species of seabird and are known to have one of the longest migrations in the world, as they travel from the Arctic to the Antarctic every year. Arctic Tern are affected by the impacts of climate change (Morten et al., 2023). These birds are also culturally significant for indigenous communities, as their eggs are important for subsistence harvesting.

## Research question
> Given that the Arctic is experiencing the effects of climate change at a much faster rate than the rest of the world, where do Arctic Tern spend most of the year and when do they migrate? How much of their year is actually spent at the poles versus actively migrating.

## Load required libraries


<script type="esms-options">{"shimMode": true}</script><style>*[data-root-id],
*[data-root-id] > * {
  box-sizing: border-box;
  font-family: var(--jp-ui-font-family);
  font-size: var(--jp-ui-font-size1);
  color: var(--vscode-editor-foreground, var(--jp-ui-font-color1));
}

/* Override VSCode background color */
.cell-output-ipywidget-background:has(
  > .cell-output-ipywidget-background > .lm-Widget > *[data-root-id]
),
.cell-output-ipywidget-background:has(> .lm-Widget > *[data-root-id]) {
  background-color: transparent !important;
}
</style>







<div id='p1011'>
  <div id="e52e72d8-b040-4217-8d31-b38bbc16829a" data-root-id="p1011" style="display: contents;"></div>
</div>
<script type="application/javascript">(function(root) {
  var docs_json = {"b32e1bdb-cfd0-4075-91e2-a524e9fd2e2f":{"version":"3.9.2","title":"Bokeh Application","config":{"type":"object","name":"DocumentConfig","id":"p1009","attributes":{"notifications":{"type":"object","name":"Notifications","id":"p1010"}}},"roots":[{"type":"object","name":"panel.models.browser.BrowserInfo","id":"p1011"},{"type":"object","name":"panel.models.comm_manager.CommManager","id":"p1012","attributes":{"plot_id":"p1011","comm_id":"28a841d671904351aefb74803b684e5a","client_comm_id":"24e0d1affda14b7182168a15863a1423"}}],"defs":[{"type":"model","name":"ReactiveHTML1"},{"type":"model","name":"FlexBox1","properties":[{"name":"align_content","kind":"Any","default":"flex-start"},{"name":"align_items","kind":"Any","default":"flex-start"},{"name":"flex_direction","kind":"Any","default":"row"},{"name":"flex_wrap","kind":"Any","default":"wrap"},{"name":"gap","kind":"Any","default":""},{"name":"justify_content","kind":"Any","default":"flex-start"}]},{"type":"model","name":"FloatPanel1","properties":[{"name":"config","kind":"Any","default":{"type":"map"}},{"name":"contained","kind":"Any","default":true},{"name":"position","kind":"Any","default":"right-top"},{"name":"offsetx","kind":"Any","default":null},{"name":"offsety","kind":"Any","default":null},{"name":"theme","kind":"Any","default":"primary"},{"name":"status","kind":"Any","default":"normalized"}]},{"type":"model","name":"GridStack1","properties":[{"name":"ncols","kind":"Any","default":null},{"name":"nrows","kind":"Any","default":null},{"name":"allow_resize","kind":"Any","default":true},{"name":"allow_drag","kind":"Any","default":true},{"name":"state","kind":"Any","default":[]}]},{"type":"model","name":"drag1","properties":[{"name":"slider_width","kind":"Any","default":5},{"name":"slider_color","kind":"Any","default":"black"},{"name":"start","kind":"Any","default":0},{"name":"end","kind":"Any","default":100},{"name":"value","kind":"Any","default":50}]},{"type":"model","name":"click1","properties":[{"name":"terminal_output","kind":"Any","default":""},{"name":"debug_name","kind":"Any","default":""},{"name":"clears","kind":"Any","default":0}]},{"type":"model","name":"ReactiveESM1","properties":[{"name":"esm_constants","kind":"Any","default":{"type":"map"}}]},{"type":"model","name":"JSComponent1","properties":[{"name":"esm_constants","kind":"Any","default":{"type":"map"}}]},{"type":"model","name":"ReactComponent1","properties":[{"name":"use_shadow_dom","kind":"Any","default":true},{"name":"esm_constants","kind":"Any","default":{"type":"map"}}]},{"type":"model","name":"AnyWidgetComponent1","properties":[{"name":"use_shadow_dom","kind":"Any","default":true},{"name":"esm_constants","kind":"Any","default":{"type":"map"}}]},{"type":"model","name":"FastWrapper1","properties":[{"name":"object","kind":"Any","default":null},{"name":"style","kind":"Any","default":null}]},{"type":"model","name":"NotificationArea1","properties":[{"name":"js_events","kind":"Any","default":{"type":"map"}},{"name":"max_notifications","kind":"Any","default":5},{"name":"notifications","kind":"Any","default":[]},{"name":"position","kind":"Any","default":"bottom-right"},{"name":"_clear","kind":"Any","default":0},{"name":"types","kind":"Any","default":[{"type":"map","entries":[["type","warning"],["background","#ffc107"],["icon",{"type":"map","entries":[["className","fas fa-exclamation-triangle"],["tagName","i"],["color","white"]]}]]},{"type":"map","entries":[["type","info"],["background","#007bff"],["icon",{"type":"map","entries":[["className","fas fa-info-circle"],["tagName","i"],["color","white"]]}]]}]}]},{"type":"model","name":"Notification","properties":[{"name":"background","kind":"Any","default":null},{"name":"duration","kind":"Any","default":3000},{"name":"icon","kind":"Any","default":null},{"name":"message","kind":"Any","default":""},{"name":"notification_type","kind":"Any","default":null},{"name":"_rendered","kind":"Any","default":false},{"name":"_destroyed","kind":"Any","default":false}]},{"type":"model","name":"TemplateActions1","properties":[{"name":"open_modal","kind":"Any","default":0},{"name":"close_modal","kind":"Any","default":0}]},{"type":"model","name":"BootstrapTemplateActions1","properties":[{"name":"open_modal","kind":"Any","default":0},{"name":"close_modal","kind":"Any","default":0}]},{"type":"model","name":"TemplateEditor1","properties":[{"name":"layout","kind":"Any","default":[]}]},{"type":"model","name":"MaterialTemplateActions1","properties":[{"name":"open_modal","kind":"Any","default":0},{"name":"close_modal","kind":"Any","default":0}]},{"type":"model","name":"request_value1","properties":[{"name":"fill","kind":"Any","default":"none"},{"name":"_synced","kind":"Any","default":null},{"name":"_request_sync","kind":"Any","default":0}]}]}};
  var render_items = [{"docid":"b32e1bdb-cfd0-4075-91e2-a524e9fd2e2f","roots":{"p1011":"e52e72d8-b040-4217-8d31-b38bbc16829a"},"root_ids":["p1011"]}];
  var docs = Object.values(docs_json)
  if (!docs) {
    return
  }
  const version = docs[0].version.replace('rc', '-rc.').replace('.dev', '-dev.')
  async function embed_document(root) {
    var Bokeh = get_bokeh(root)
    await Bokeh.embed.embed_items_notebook(docs_json, render_items);
    for (const render_item of render_items) {
      for (const root_id of render_item.root_ids) {
	const id_el = document.getElementById(root_id)
	if (id_el.children.length && id_el.children[0].hasAttribute('data-root-id')) {
	  const root_el = id_el.children[0]
	  root_el.id = root_el.id + '-rendered'
	  for (const child of root_el.children) {
            // Ensure JupyterLab does not capture keyboard shortcuts
            // see: https://jupyterlab.readthedocs.io/en/4.1.x/extension/notebook.html#keyboard-interaction-model
	    child.setAttribute('data-lm-suppress-shortcuts', 'true')
	  }
	}
      }
    }
  }
  function get_bokeh(root) {
    if (root.Bokeh === undefined) {
      return null
    } else if (root.Bokeh.version !== version) {
      if (root.Bokeh.versions === undefined || !root.Bokeh.versions.has(version)) {
	return null
      }
      return root.Bokeh.versions.get(version);
    } else if (root.Bokeh.version === version) {
      return root.Bokeh
    }
    return null
  }
  function is_loaded(root) {
    var Bokeh = get_bokeh(root)
    return (Bokeh != null && Bokeh.Panel !== undefined)
  }
  if (is_loaded(root)) {
    embed_document(root);
  } else {
    var attempts = 0;
    var timer = setInterval(function(root) {
      if (is_loaded(root)) {
        clearInterval(timer);
        embed_document(root);
      } else if (document.readyState == "complete") {
        attempts++;
        if (attempts > 200) {
          clearInterval(timer);
	  var Bokeh = get_bokeh(root)
	  if (Bokeh == null || Bokeh.Panel == null) {
            console.warn("Panel: ERROR: Unable to run Panel code because Bokeh or Panel library is missing");
	  } else {
	    console.warn("Panel: WARNING: Attempting to render but not all required libraries could be resolved.")
	    embed_document(root)
	  }
        }
      }
    }, 25, root)
  }
})(window);</script>


## Create directory for data

## Download and plot ecoregions

## Load GBIF data
**Species Occurrence Data:** The data we're using comes from the Global Biodiversity Information Facility (GBIF) website (https://www.gbif.org/taxon/6ZSDC), which reports geospatial species occurrence data. Specifically, we're using Arctic Tern data from 2020. 
**Ecoregion Data:** 




    <Axes: title={'center': 'Normalized Occurrences by Month and Ecoregion (2020)'}, xlabel='Month', ylabel='Normalized Occurrences'>




    
![png](06-portfolio-post_files/06-portfolio-post_13_1.png)
    


> This scatterplot shows us the normalized occurrences of Arctic Tern by month and ecoregion. We can see that at the start of the year, Arctic Tern are seen in 3 main ecoregions which are located near the poles. As the year goes on and we move towards summer in the northern hemisphere, we see Arctic Tern in a wider range of ecoregions in both polar and temperate regions, with low occurrences across ecoregions. Moving from June to October, we see a decrease in the number of ecoregions and an increase in the normalized occurrences in each of these ecoregions. From October to December, we see a gradual decrease in the number of ecoregions, with most occurrences shifting to polar regions, and the normalized occurrences in the few regions with Arctic Terns gradually increased as the number of ecoregions decreased.


<script type="esms-options">{"shimMode": true}</script><style>*[data-root-id],
*[data-root-id] > * {
  box-sizing: border-box;
  font-family: var(--jp-ui-font-family);
  font-size: var(--jp-ui-font-size1);
  color: var(--vscode-editor-foreground, var(--jp-ui-font-color1));
}

/* Override VSCode background color */
.cell-output-ipywidget-background:has(
  > .cell-output-ipywidget-background > .lm-Widget > *[data-root-id]
),
.cell-output-ipywidget-background:has(> .lm-Widget > *[data-root-id]) {
  background-color: transparent !important;
}
</style>







<div id='454f9dfe-de17-4617-9a3d-a6d061506714'>
  <div id="fa013cfc-cd63-4812-8798-355f881d62e5" data-root-id="454f9dfe-de17-4617-9a3d-a6d061506714" style="display: contents;"></div>
</div>
<script type="application/javascript">(function(root) {
  var docs_json = {"aee524d5-9e0d-4638-b12b-2478a8fb12f7":{"version":"3.9.2","title":"Bokeh Application","config":{"type":"object","name":"DocumentConfig","id":"ccc2975c-4e39-4ee2-b43a-9a17b4f5ad46","attributes":{"notifications":{"type":"object","name":"Notifications","id":"af39a1db-abd2-4366-a8ff-2fe237bb614c"}}},"roots":[{"type":"object","name":"panel.models.browser.BrowserInfo","id":"454f9dfe-de17-4617-9a3d-a6d061506714"},{"type":"object","name":"panel.models.comm_manager.CommManager","id":"40e06df0-fae5-46c6-acc0-cf80d4e4103a","attributes":{"plot_id":"454f9dfe-de17-4617-9a3d-a6d061506714","comm_id":"26ab9c73d7a749479638041ce79a237d","client_comm_id":"0cd5f7bd7a6f4119aecf67533e24d76b"}}],"defs":[{"type":"model","name":"ReactiveHTML1"},{"type":"model","name":"FlexBox1","properties":[{"name":"align_content","kind":"Any","default":"flex-start"},{"name":"align_items","kind":"Any","default":"flex-start"},{"name":"flex_direction","kind":"Any","default":"row"},{"name":"flex_wrap","kind":"Any","default":"wrap"},{"name":"gap","kind":"Any","default":""},{"name":"justify_content","kind":"Any","default":"flex-start"}]},{"type":"model","name":"FloatPanel1","properties":[{"name":"config","kind":"Any","default":{"type":"map"}},{"name":"contained","kind":"Any","default":true},{"name":"position","kind":"Any","default":"right-top"},{"name":"offsetx","kind":"Any","default":null},{"name":"offsety","kind":"Any","default":null},{"name":"theme","kind":"Any","default":"primary"},{"name":"status","kind":"Any","default":"normalized"}]},{"type":"model","name":"GridStack1","properties":[{"name":"ncols","kind":"Any","default":null},{"name":"nrows","kind":"Any","default":null},{"name":"allow_resize","kind":"Any","default":true},{"name":"allow_drag","kind":"Any","default":true},{"name":"state","kind":"Any","default":[]}]},{"type":"model","name":"drag1","properties":[{"name":"slider_width","kind":"Any","default":5},{"name":"slider_color","kind":"Any","default":"black"},{"name":"start","kind":"Any","default":0},{"name":"end","kind":"Any","default":100},{"name":"value","kind":"Any","default":50}]},{"type":"model","name":"click1","properties":[{"name":"terminal_output","kind":"Any","default":""},{"name":"debug_name","kind":"Any","default":""},{"name":"clears","kind":"Any","default":0}]},{"type":"model","name":"ReactiveESM1","properties":[{"name":"esm_constants","kind":"Any","default":{"type":"map"}}]},{"type":"model","name":"JSComponent1","properties":[{"name":"esm_constants","kind":"Any","default":{"type":"map"}}]},{"type":"model","name":"ReactComponent1","properties":[{"name":"use_shadow_dom","kind":"Any","default":true},{"name":"esm_constants","kind":"Any","default":{"type":"map"}}]},{"type":"model","name":"AnyWidgetComponent1","properties":[{"name":"use_shadow_dom","kind":"Any","default":true},{"name":"esm_constants","kind":"Any","default":{"type":"map"}}]},{"type":"model","name":"FastWrapper1","properties":[{"name":"object","kind":"Any","default":null},{"name":"style","kind":"Any","default":null}]},{"type":"model","name":"NotificationArea1","properties":[{"name":"js_events","kind":"Any","default":{"type":"map"}},{"name":"max_notifications","kind":"Any","default":5},{"name":"notifications","kind":"Any","default":[]},{"name":"position","kind":"Any","default":"bottom-right"},{"name":"_clear","kind":"Any","default":0},{"name":"types","kind":"Any","default":[{"type":"map","entries":[["type","warning"],["background","#ffc107"],["icon",{"type":"map","entries":[["className","fas fa-exclamation-triangle"],["tagName","i"],["color","white"]]}]]},{"type":"map","entries":[["type","info"],["background","#007bff"],["icon",{"type":"map","entries":[["className","fas fa-info-circle"],["tagName","i"],["color","white"]]}]]}]}]},{"type":"model","name":"Notification","properties":[{"name":"background","kind":"Any","default":null},{"name":"duration","kind":"Any","default":3000},{"name":"icon","kind":"Any","default":null},{"name":"message","kind":"Any","default":""},{"name":"notification_type","kind":"Any","default":null},{"name":"_rendered","kind":"Any","default":false},{"name":"_destroyed","kind":"Any","default":false}]},{"type":"model","name":"TemplateActions1","properties":[{"name":"open_modal","kind":"Any","default":0},{"name":"close_modal","kind":"Any","default":0}]},{"type":"model","name":"BootstrapTemplateActions1","properties":[{"name":"open_modal","kind":"Any","default":0},{"name":"close_modal","kind":"Any","default":0}]},{"type":"model","name":"TemplateEditor1","properties":[{"name":"layout","kind":"Any","default":[]}]},{"type":"model","name":"MaterialTemplateActions1","properties":[{"name":"open_modal","kind":"Any","default":0},{"name":"close_modal","kind":"Any","default":0}]},{"type":"model","name":"request_value1","properties":[{"name":"fill","kind":"Any","default":"none"},{"name":"_synced","kind":"Any","default":null},{"name":"_request_sync","kind":"Any","default":0}]}]}};
  var render_items = [{"docid":"aee524d5-9e0d-4638-b12b-2478a8fb12f7","roots":{"454f9dfe-de17-4617-9a3d-a6d061506714":"fa013cfc-cd63-4812-8798-355f881d62e5"},"root_ids":["454f9dfe-de17-4617-9a3d-a6d061506714"]}];
  var docs = Object.values(docs_json)
  if (!docs) {
    return
  }
  const version = docs[0].version.replace('rc', '-rc.').replace('.dev', '-dev.')
  async function embed_document(root) {
    var Bokeh = get_bokeh(root)
    await Bokeh.embed.embed_items_notebook(docs_json, render_items);
    for (const render_item of render_items) {
      for (const root_id of render_item.root_ids) {
	const id_el = document.getElementById(root_id)
	if (id_el.children.length && id_el.children[0].hasAttribute('data-root-id')) {
	  const root_el = id_el.children[0]
	  root_el.id = root_el.id + '-rendered'
	  for (const child of root_el.children) {
            // Ensure JupyterLab does not capture keyboard shortcuts
            // see: https://jupyterlab.readthedocs.io/en/4.1.x/extension/notebook.html#keyboard-interaction-model
	    child.setAttribute('data-lm-suppress-shortcuts', 'true')
	  }
	}
      }
    }
  }
  function get_bokeh(root) {
    if (root.Bokeh === undefined) {
      return null
    } else if (root.Bokeh.version !== version) {
      if (root.Bokeh.versions === undefined || !root.Bokeh.versions.has(version)) {
	return null
      }
      return root.Bokeh.versions.get(version);
    } else if (root.Bokeh.version === version) {
      return root.Bokeh
    }
    return null
  }
  function is_loaded(root) {
    var Bokeh = get_bokeh(root)
    return (Bokeh != null && Bokeh.Panel !== undefined)
  }
  if (is_loaded(root)) {
    embed_document(root);
  } else {
    var attempts = 0;
    var timer = setInterval(function(root) {
      if (is_loaded(root)) {
        clearInterval(timer);
        embed_document(root);
      } else if (document.readyState == "complete") {
        attempts++;
        if (attempts > 200) {
          clearInterval(timer);
	  var Bokeh = get_bokeh(root)
	  if (Bokeh == null || Bokeh.Panel == null) {
            console.warn("Panel: ERROR: Unable to run Panel code because Bokeh or Panel library is missing");
	  } else {
	    console.warn("Panel: WARNING: Attempting to render but not all required libraries could be resolved.")
	    embed_document(root)
	  }
        }
      }
    }, 25, root)
  }
})(window);</script>



<script type="esms-options">{"shimMode": true}</script><style>*[data-root-id],
*[data-root-id] > * {
  box-sizing: border-box;
  font-family: var(--jp-ui-font-family);
  font-size: var(--jp-ui-font-size1);
  color: var(--vscode-editor-foreground, var(--jp-ui-font-color1));
}

/* Override VSCode background color */
.cell-output-ipywidget-background:has(
  > .cell-output-ipywidget-background > .lm-Widget > *[data-root-id]
),
.cell-output-ipywidget-background:has(> .lm-Widget > *[data-root-id]) {
  background-color: transparent !important;
}
</style>






                                                   

    WARNING:bokeh.core.validation.check:W-1005 (FIXED_SIZING_MODE): 'fixed' sizing mode requires width and height to be set: figure(id='777d1cde-5f74-4a91-9265-02a4ae044da4', ...)
    

    




    BokehModel(combine_events=True, render_bundle={'docs_json': {'41ffc558-b2b1-47fe-9c59-7ce1c5975822': {'version…



## Interactive Map
> Another way of visualizing the data seen in the previously shown scatterplot is in an interactive map. Here, we show the spatial distribution of Arctic Tern by month. This gives us insight into some of the trends in migration patterns that may exist for this species. 

## Limitations
> Some limitations that are important to note include the fact that the occurrence data used here is limited by observations.

## Bibliography

> Morten, J. M., Buchanan, P. J., Egevang, C., Glissenaar, I. A., Maxwell, S. M., Parr, N., Screen, J. A., Vigfusdottir, F., Vogt-Vincent, N., S., Williams, D. A. (2023) Global warming and arctic terns: Estimating climate change impacts on the world's longest migration. Global Change Biology. https://doi.org/10.1111/gbc.16891
>
>Alerstam, T., Backman, J., Gronroos, J., Olofsson, P., Strandberg, R. (2019) Hypotheses and tracking results about the longest migration: The case of the arctic tern. Ecology and Evolution. https://doi.org/10.1002/ece3.5459

    [NbConvertApp] Converting notebook 06-portfolio-post.ipynb to html
    [NbConvertApp] WARNING | Alternative text is missing on 1 image(s).
    [NbConvertApp] Writing 445945 bytes to 06-portfolio-post.html
    
