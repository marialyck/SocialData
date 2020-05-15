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

<img src="https://github.com/marialyck/SocialData/blob/master/bas1.png" alt="hi" class="inline"/>

[![image](https://github.com/marialyck/SocialData/blob/master/bas1.png)]

So the fatal accidents are shown in the following plot and surprisingly it is not Friday night that the worst accidents happens. It turns out to be Saturday... hmmm. Surprised?
[![image](https://github.com/marialyck/SocialData/blob/master/bas2.png)]







# fun fact:
:bowtie: 

Of all the accidents in 2018, 25390 were in London.

That is 20000 more that any other single county in the UK.

On a second place comes West midlands with 5490.

The county with least recorded accidents is Dumfries and Galloway, with only 258 recorded accidents.

:bowtie: 








:bowtie: 

In britain by all regrestret car accidents in 2018, did you know that only 23.35% of all accidents are coursed with a female behind the sterringwheel. 

#### Translated... 
males are responsible for the last 76.65%, that is over double the amount of accidents as females. This might reject the stereotypical attitude about females and their driving skills. But lets dig a little deeper, to get a better understanding...

:bowtie: 

[![image](https://github.com/marialyck/SocialData/blob/master/bas3.png)]


<iframe id="inlineFrameExample"
    title="Inline Frame Example"
    width="1200"
    height="400"
    src="https://severin.edea.dk/SD/interactive4.html">
</iframe>



<iframe id="inlineFrameExample"
    title="Inline Frame Example"
    width="1000"
    height="500"
    src="https://severin.edea.dk/SD/map_14.html">
</iframe>

<html><head>

<!-- Load require.js. Delete this if your page already loads require.js -->
<script src="https://cdnjs.cloudflare.com/ajax/libs/require.js/2.3.4/require.min.js" integrity="sha256-Ae2Vz/4ePdIu6ZyI/5ZGsYnb+m0JlOmKPjt6XZ9JJkA=" crossorigin="anonymous"></script>
<script src="https://unpkg.com/@jupyter-widgets/html-manager@*/dist/embed-amd.js" crossorigin="anonymous"></script>
<script type="application/vnd.jupyter.widget-state+json">
{
    "version_major": 2,
    "version_minor": 0,
    "state": {
        "514d9bf210d74a3cb6e407bf6131eba8": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "f3cc73ca6a044ddba7e8dd1dd802b7e7": {
            "model_name": "SliderStyleModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "description_width": ""
            }
        },
        "285fa9322dbd4241bc2783c728e76af8": {
            "model_name": "IntSliderModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "description": "Age:",
                "layout": "IPY_MODEL_514d9bf210d74a3cb6e407bf6131eba8",
                "max": 101,
                "min": 15,
                "style": "IPY_MODEL_f3cc73ca6a044ddba7e8dd1dd802b7e7",
                "value": 15
            }
        },
        "b0710cbf4f9846989966853c423cfc25": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "287fa7869b99415b960d0de5a1baee7f": {
            "model_name": "ToggleButtonsStyleModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "button_width": "",
                "description_width": ""
            }
        },
        "f3f439ceb4404ba992cf905d78262bc6": {
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
                "layout": "IPY_MODEL_b0710cbf4f9846989966853c423cfc25",
                "style": "IPY_MODEL_287fa7869b99415b960d0de5a1baee7f",
                "tooltips": []
            }
        },
        "5789009bbf664d0a9d8488536288a3fc": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "f7c30f7a229047baa48acb1aa56267cc": {
            "model_name": "ToggleButtonsStyleModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "button_width": "",
                "description_width": ""
            }
        },
        "6f6bd826e6774b7f8bf6b44d2339ceb7": {
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
                "layout": "IPY_MODEL_5789009bbf664d0a9d8488536288a3fc",
                "style": "IPY_MODEL_f7c30f7a229047baa48acb1aa56267cc",
                "tooltips": []
            }
        },
        "4ea69d2c7a0944539d7f2883740b28fd": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "0b93d09cedf04ab992988ce3ae542c84": {
            "model_name": "ToggleButtonsStyleModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "button_width": "",
                "description_width": ""
            }
        },
        "6d9c7085b9534f8b9f53055aa0ba56db": {
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
                "layout": "IPY_MODEL_4ea69d2c7a0944539d7f2883740b28fd",
                "style": "IPY_MODEL_0b93d09cedf04ab992988ce3ae542c84",
                "tooltips": []
            }
        },
        "0efac6bead9c40bc829f4301545debcc": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "3737ef7f915a4146a12a6e010cbc5eaa": {
            "model_name": "ButtonStyleModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {}
        },
        "66dfae3edb43411bb7930e79070fecb6": {
            "model_name": "ButtonModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "description": "Calculate",
                "layout": "IPY_MODEL_0efac6bead9c40bc829f4301545debcc",
                "style": "IPY_MODEL_3737ef7f915a4146a12a6e010cbc5eaa"
            }
        },
        "9db12bd064ac418fa7932081cbe3e6d3": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "e4373b3e9f8b480598039fa8c92ab17c": {
            "model_name": "OutputModel",
            "model_module": "@jupyter-widgets/output",
            "model_module_version": "1.0.0",
            "state": {
                "layout": "IPY_MODEL_9db12bd064ac418fa7932081cbe3e6d3"
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
    "model_id": "f3f439ceb4404ba992cf905d78262bc6"
}
</script>

<script type="application/vnd.jupyter.widget-view+json">
{
    "version_major": 2,
    "version_minor": 0,
    "model_id": "285fa9322dbd4241bc2783c728e76af8"
}
</script>

<script type="application/vnd.jupyter.widget-view+json">
{
    "version_major": 2,
    "version_minor": 0,
    "model_id": "6f6bd826e6774b7f8bf6b44d2339ceb7"
}
</script>

<script type="application/vnd.jupyter.widget-view+json">
{
    "version_major": 2,
    "version_minor": 0,
    "model_id": "6d9c7085b9534f8b9f53055aa0ba56db"
}
</script>

<script type="application/vnd.jupyter.widget-view+json">
{
    "version_major": 2,
    "version_minor": 0,
    "model_id": "66dfae3edb43411bb7930e79070fecb6"
}
</script>

<script type="application/vnd.jupyter.widget-view+json">
{
    "version_major": 2,
    "version_minor": 0,
    "model_id": "e4373b3e9f8b480598039fa8c92ab17c"
}
</script>

</body>
</html>

If you experience troubles with the calculations then try our noteebook. (We have had a bit of some troubles with the calculation button on the homepage) 
