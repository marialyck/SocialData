For explainer notebook please look here:

<!-- Place this tag where you want the button to render. -->
<a class="github-button" href="https://drive.google.com/open?id=1Jpiilh3af5drumnxuNi1sb8GyIvJIGVH" data-icon="octicon-heart" aria-label="Explainer">Explainer</a>


# When is it safe to drive in the UK?

Have you ever wondered what is the safest path from A to B? What places to avoid in the traffic?
### So have we. 

But looking to line after line of data trying to wrap your head around what is the safest path can be a struggle. Hopefully you will bee abl to get a better idea of that afteer reading this article. With interactive plots you will b ablee to visualise through the roadsafety. 

[![Youtube video example](https://media.giphy.com/media/OH2rL6DVTNpte/giphy.gif)](https://www.youtube.com/watch?v=Z_CfUWdqcpI "The apetiser video")

In this article, you will have the opportunity to investigate, if you drive at a safe time and distance.
What factors do you believe has and impact on the day to day safety on the road? 

In 2018, 122635 accidents were registered at the authorities. Looking a bit closer these accidents can be divided into three categories, with regards to the severity.

_Fatal: 1671 accidents_

_Serious: 23165 accidents_

_Slight: 97799 accidents_ 

Let us take a dive into the heatmap and see how it is spread across London:

Try to adjust the slider and see if it impacts the number of accidents. The hours are just an overall average of how accidents are in UK. However let's have a fokus on London. It seems like this is here the heat is on. 

<iframe id="inlineFrameExample"
    title="Inline Frame Example"
    width="1000"
    height="500"
    src="https://severin.edea.dk/SD/heatmap.html">
</iframe>

Are you surprised by the result? 

We see that the distribution of accidents clearly rise when rush hour starts, and the majority of accidents happens in the hours from 6 AM to 6PM.

Well it makes sense does it not? 

There is a lot of people on the road at these hours. Or at least our logic tells us that's the case.

It can observed that Slight and Serious accidents spike at rush hour, but that Fatal accidents has a more even distribution.



Let us dig a little deeper.

In these two plots you can investigate the different severities of accidents over from a entire year, distributed over 24 hours.

The first graph shows the accidents accumulated over a year. It did not come as a major surprise that Friday has a higher part of accidents. The bars are open and people don't work Saturday, but of course that is an assumptiom. Let's dig even a little deeper.
<iframe id="inlineFrameExample"
    title="Inline Frame Example"
    width="1000"
    height="500"
    src="https://severin.edea.dk/SD/bas1.png">
</iframe>

So the fatal accidents are shown in the following plot and surprisingly it is not Friday night that the worst accidents happens. It turns out to be Saturday... hmmm. Surprised?
<iframe id="inlineFrameExample"
    title="Inline Frame Example"
    width="1000"
    height="500"
    src="https://severin.edea.dk/SD/bas2.png">
</iframe>


# fun fact:
:bowtie: 

Of all the accidents in 2018, 25390 were in London.

That is 20000 more that any other single county in the UK.

On a second place comes West midlands with 5490.

The county with least recorded accidents is Dumfries and Galloway, with only 258 recorded accidents.

:bowtie: 

Have a look at our map
<iframe id="inlineFrameExample"
    title="Inline Frame Example"
    width="1000"
    height="500"
    src="https://severin.edea.dk/SD/map_14.html">
</iframe>

It clusters the accidents and show where the accidents have happened. 

### funfact

:bowtie: 

In britain by all regrestret car accidents in 2018, did you know that only 23.35% of all accidents are coursed with a female behind the sterringwheel. 

#### Translated... 
males are responsible for the last 76.65%, that is over double the amount of accidents as females. This might reject the stereotypical attitude about females and their driving skills. But lets dig a little deeper, to get a better understanding...

:bowtie: 

See that is not a surprise. Then one can think that this is because men tend to drive wilder than women or that looking inside cars passing by one might notice that most of the time the men are behind the wheels. This is not something we are going to conclude on. We will leave that up to you...

<iframe id="inlineFrameExample"
    title="Inline Frame Example"
    width="1200"
    height="400"
    src="https://severin.edea.dk/SD/interactive4.html">
</iframe>


### Yet a funfact

:bowtie: 

In britain by all regrestret car accidents in 2018, did you know that only 23.35% of all accidents are coursed with a female behind the sterringwheel. Translated... males are responsible for the last 76.65%, that is over double the amount of accidents as females. This might reject the stereotypical attitude about females and their driving skills. But lets dig a little deeper, to get a better understanding...

:bowtie: 

If you experience troubles with the calculations then try our noteebook. (We have had a bit of some troubles with the calculation button on the homepage) 

<html><head>


<!-- Load require.js. Delete this if your page already loads require.js -->
<script src="https://cdnjs.cloudflare.com/ajax/libs/require.js/2.3.4/require.min.js" integrity="sha256-Ae2Vz/4ePdIu6ZyI/5ZGsYnb+m0JlOmKPjt6XZ9JJkA=" crossorigin="anonymous"></script>
<script src="https://unpkg.com/@jupyter-widgets/html-manager@*/dist/embed-amd.js" crossorigin="anonymous"></script>
<script type="application/vnd.jupyter.widget-state+json">
{
    "version_major": 2,
    "version_minor": 0,
    "state": {
        "72d86ce7c5514ddcb201df0e76958e17": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "6849b65dd5674b82a9188221d2833d18": {
            "model_name": "SliderStyleModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "description_width": ""
            }
        },
        "759912b6f5b144b7a19cbe24106c1372": {
            "model_name": "IntSliderModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "description": "Age:",
                "layout": "IPY_MODEL_72d86ce7c5514ddcb201df0e76958e17",
                "max": 101,
                "min": 15,
                "style": "IPY_MODEL_6849b65dd5674b82a9188221d2833d18",
                "value": 15
            }
        },
        "d5185f2333df49b1bf08c7507c23949a": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "f7c78bb171e24785948abe6255a7e51e": {
            "model_name": "ToggleButtonsStyleModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "button_width": "",
                "description_width": ""
            }
        },
        "e9d6fc307df3432dbc67cc28b557e664": {
            "model_name": "ToggleButtonsModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "_options_labels": [
                    "Male",
                    "Female"
                ],
                "button_style": "",
                "description": "Vehicle:",
                "icons": [],
                "index": 0,
                "layout": "IPY_MODEL_d5185f2333df49b1bf08c7507c23949a",
                "style": "IPY_MODEL_f7c78bb171e24785948abe6255a7e51e",
                "tooltips": []
            }
        },
        "182f53408fc341908916a687bfd94799": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "628c2b69ee744ecd881149c611c39d22": {
            "model_name": "ToggleButtonsStyleModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "button_width": "",
                "description_width": ""
            }
        },
        "70e2148396dc45569388be42daccccbb": {
            "model_name": "ToggleButtonsModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "_options_labels": [
                    "Pedal cycle",
                    "Motorcycle",
                    "Taxi",
                    "Car",
                    "Bus",
                    "Ridden horse",
                    "Goods transporter",
                    "Mobility scooter"
                ],
                "button_style": "",
                "description": "Transport type:",
                "icons": [],
                "index": 0,
                "layout": "IPY_MODEL_182f53408fc341908916a687bfd94799",
                "style": "IPY_MODEL_628c2b69ee744ecd881149c611c39d22",
                "tooltips": []
            }
        },
        "a1370e0179614efdad29f917cebf3e1e": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "b99b9f8115144a20a79a53f7355a8ed5": {
            "model_name": "ToggleButtonsStyleModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "button_width": "",
                "description_width": ""
            }
        },
        "175065be1e574bccbd2a2dcd5d96a3e6": {
            "model_name": "ToggleButtonsModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "_options_labels": [
                    "Previous accident",
                    "Road works",
                    "Parked vehicle",
                    "Bridge",
                    "Bollard or refuge",
                    "Open door of vehicle",
                    "Center of roundabout",
                    "Kerb",
                    "Animal"
                ],
                "button_style": "",
                "description": "Vehicle:",
                "icons": [],
                "index": 0,
                "layout": "IPY_MODEL_a1370e0179614efdad29f917cebf3e1e",
                "style": "IPY_MODEL_b99b9f8115144a20a79a53f7355a8ed5",
                "tooltips": []
            }
        },
        "b8d33587cfeb4ea59498fae7780b4398": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "c5e7e489296e4bccb8f17df8cdb43ddd": {
            "model_name": "ButtonStyleModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {}
        },
        "bd306a0503894565a335bd9226106d5e": {
            "model_name": "ButtonModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "description": "Calculate",
                "layout": "IPY_MODEL_b8d33587cfeb4ea59498fae7780b4398",
                "style": "IPY_MODEL_c5e7e489296e4bccb8f17df8cdb43ddd"
            }
        },
        "fc851e0225a647f9b849272312aecf20": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "4ab4001e6ba44bae9033d6d3acef5cd4": {
            "model_name": "OutputModel",
            "model_module": "@jupyter-widgets/output",
            "model_module_version": "1.0.0",
            "state": {
                "layout": "IPY_MODEL_fc851e0225a647f9b849272312aecf20"
            }
        }
    }
}
</script>
</head>
<body>

<script type="application/vnd.jupyter.widget-view+json">
{
    "version_major": 2,
    "version_minor": 0,
    "model_id": "e9d6fc307df3432dbc67cc28b557e664"
}
</script>

<script type="application/vnd.jupyter.widget-view+json">
{
    "version_major": 2,
    "version_minor": 0,
    "model_id": "759912b6f5b144b7a19cbe24106c1372"
}
</script>

<script type="application/vnd.jupyter.widget-view+json">
{
    "version_major": 2,
    "version_minor": 0,
    "model_id": "70e2148396dc45569388be42daccccbb"
}
</script>

<script type="application/vnd.jupyter.widget-view+json">
{
    "version_major": 2,
    "version_minor": 0,
    "model_id": "175065be1e574bccbd2a2dcd5d96a3e6"
}
</script>

<script type="application/vnd.jupyter.widget-view+json">
{
    "version_major": 2,
    "version_minor": 0,
    "model_id": "bd306a0503894565a335bd9226106d5e"
}
</script>

<script type="application/vnd.jupyter.widget-view+json">
{
    "version_major": 2,
    "version_minor": 0,
    "model_id": "4ab4001e6ba44bae9033d6d3acef5cd4"
}
</script>

</body>
</html>



So when do all this happen? If we conclude that women are better drivers (Oh this is a dangerous gender based one) the why do the accidents happen? Is it on the way to school, work, someething else?


<iframe id="inlineFrameExample"
    title="Inline Frame Example"
    width="1000"
    height="500"
    src="https://severin.edea.dk/SD/ch4.png">
</iframe>




So apparently it is going to work that is the main factor. Can we by that conclude that the women in UK doesn't work? Knowing some few facts about UK (such as a daycare spot cost app. 800 Pounds a month it is not unrealistic that there is a majority of the men working - source is from several british friends) However it is not concluded that women doesn't work and hence the men are contributing with all the accidents

For a more secure walk through you will be able to see in our notebook which streetcorneers to avoid. 

Lastly you could also just consider going on really slow or really fast?

<iframe id="inlineFrameExample"
    title="Inline Frame Example"
    width="1000"
    height="500"
    src="https://severin.edea.dk/SD/slow.png">
</iframe>

Looking to the different aspects of these stats it is safe to conclude that London is a city with a lot of accidents. Some streets are safer than others and if you are a newbie to the traffic - avoid the clusters ...

# Drive safe



