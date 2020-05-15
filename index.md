For explainer notebook please look here:

https://drive.google.com/open?id=1Jpiilh3af5drumnxuNi1sb8GyIvJIGVH

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

So when do all this happen? If we conclude that women are better drivers (Oh this is a dangerous gender based one) the why do the accidents happen? Is it on the way to school, work, someething else?
<iframe id="inlineFrameExample"
    title="Inline Frame Example"
    width="1000"
    height="500"
    src="hhttps://severin.edea.dk/SD/ch4.pngg">
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
        "da6db2c79858481389b75418f85b01af": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "1925e19e0ef54b3faf2b8354f08d1bfd": {
            "model_name": "SliderStyleModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "description_width": ""
            }
        },
        "4fc87ab0cf2f45e3addda616832718dc": {
            "model_name": "IntSliderModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "description": "Age:",
                "layout": "IPY_MODEL_da6db2c79858481389b75418f85b01af",
                "max": 101,
                "min": 15,
                "style": "IPY_MODEL_1925e19e0ef54b3faf2b8354f08d1bfd",
                "value": 15
            }
        },
        "1be2773f06354044ad700c3d9a0eabc2": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "0ceec4f737f544dc9bd7caafaddf623f": {
            "model_name": "ToggleButtonsStyleModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "button_width": "",
                "description_width": ""
            }
        },
        "860f5d8870f04ce58b3e5976cd9ee9e8": {
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
                "layout": "IPY_MODEL_1be2773f06354044ad700c3d9a0eabc2",
                "style": "IPY_MODEL_0ceec4f737f544dc9bd7caafaddf623f",
                "tooltips": []
            }
        },
        "99f2d39d014a46cdae5b53bc27192da3": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "aacb6ea1063441c485302fc077c7e728": {
            "model_name": "ToggleButtonsStyleModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "button_width": "",
                "description_width": ""
            }
        },
        "e2b0c0a85252422a9a24bfc083f16214": {
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
                "layout": "IPY_MODEL_99f2d39d014a46cdae5b53bc27192da3",
                "style": "IPY_MODEL_aacb6ea1063441c485302fc077c7e728",
                "tooltips": []
            }
        },
        "f76c2cbf3424493da78768cf90993b37": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "927a479c968048849f65ff4233948084": {
            "model_name": "ToggleButtonsStyleModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "button_width": "",
                "description_width": ""
            }
        },
        "87e3722bb5024d2d82e46b2e5ba40de4": {
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
                "index": 1,
                "layout": "IPY_MODEL_f76c2cbf3424493da78768cf90993b37",
                "style": "IPY_MODEL_927a479c968048849f65ff4233948084",
                "tooltips": []
            }
        },
        "aeccec9fa41f4ee9942563ee86cac0a4": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "7ffd362d3f7a460a9013e5e9b2b01ec5": {
            "model_name": "ButtonStyleModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {}
        },
        "8c55868dfd164456929f188862dae2ec": {
            "model_name": "ButtonModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "description": "Calculate",
                "layout": "IPY_MODEL_aeccec9fa41f4ee9942563ee86cac0a4",
                "style": "IPY_MODEL_7ffd362d3f7a460a9013e5e9b2b01ec5"
            }
        },
        "2072e731b51c450e832d197867a7ca6d": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "318e99592eae46f6806214fdc46e45f9": {
            "model_name": "OutputModel",
            "model_module": "@jupyter-widgets/output",
            "model_module_version": "1.0.0",
            "state": {
                "layout": "IPY_MODEL_2072e731b51c450e832d197867a7ca6d",
                "outputs": [
                    {
                        "output_type": "error",
                        "ename": "NotFittedError",
                        "evalue": "This RandomForestClassifier instance is not fitted yet. Call 'fit' with appropriate arguments before using this estimator.",
                        "traceback": [
                            "\u001b[0;31m---------------------------------------------------------------------------\u001b[0m",
                            "\u001b[0;31mNotFittedError\u001b[0m                            Traceback (most recent call last)",
                            "\u001b[0;32m<ipython-input-26-83befdc64328>\u001b[0m in \u001b[0;36mon_button_clicked\u001b[0;34m(b)\u001b[0m\n\u001b[1;32m     67\u001b[0m     \u001b[0;32mwith\u001b[0m \u001b[0moutput\u001b[0m\u001b[0;34m:\u001b[0m\u001b[0;34m\u001b[0m\u001b[0;34m\u001b[0m\u001b[0m\n\u001b[1;32m     68\u001b[0m \u001b[0;34m\u001b[0m\u001b[0m\n\u001b[0;32m---> 69\u001b[0;31m         \u001b[0mresult\u001b[0m \u001b[0;34m=\u001b[0m \u001b[0mpredictSeverity\u001b[0m\u001b[0;34m(\u001b[0m\u001b[0mhitobject\u001b[0m\u001b[0;34m.\u001b[0m\u001b[0mvalue\u001b[0m\u001b[0;34m,\u001b[0m \u001b[0mage\u001b[0m\u001b[0;34m.\u001b[0m\u001b[0mvalue\u001b[0m\u001b[0;34m,\u001b[0m \u001b[0mcar\u001b[0m\u001b[0;34m.\u001b[0m\u001b[0mvalue\u001b[0m\u001b[0;34m,\u001b[0m \u001b[0mgender\u001b[0m\u001b[0;34m.\u001b[0m\u001b[0mvalue\u001b[0m\u001b[0;34m)\u001b[0m\u001b[0;34m\u001b[0m\u001b[0;34m\u001b[0m\u001b[0m\n\u001b[0m\u001b[1;32m     70\u001b[0m         \u001b[0mpercentage\u001b[0m \u001b[0;34m=\u001b[0m \u001b[0mfloat\u001b[0m\u001b[0;34m(\u001b[0m\u001b[0mresult\u001b[0m\u001b[0;34m)\u001b[0m \u001b[0;34m*\u001b[0m \u001b[0;36m100\u001b[0m\u001b[0;34m\u001b[0m\u001b[0;34m\u001b[0m\u001b[0m\n\u001b[1;32m     71\u001b[0m         \u001b[0mprint\u001b[0m\u001b[0;34m(\u001b[0m\u001b[0;34m\"{:.2f}\"\u001b[0m\u001b[0;34m.\u001b[0m\u001b[0mformat\u001b[0m\u001b[0;34m(\u001b[0m\u001b[0mpercentage\u001b[0m\u001b[0;34m)\u001b[0m\u001b[0;34m)\u001b[0m\u001b[0;34m\u001b[0m\u001b[0;34m\u001b[0m\u001b[0m\n",
                            "\u001b[0;32m<ipython-input-25-336dac09e3cb>\u001b[0m in \u001b[0;36mpredictSeverity\u001b[0;34m(h, a, v, g)\u001b[0m\n\u001b[1;32m      2\u001b[0m \u001b[0;31m#The dicts from before will now be used.\u001b[0m\u001b[0;34m\u001b[0m\u001b[0;34m\u001b[0m\u001b[0;34m\u001b[0m\u001b[0m\n\u001b[1;32m      3\u001b[0m \u001b[0;32mdef\u001b[0m \u001b[0mpredictSeverity\u001b[0m \u001b[0;34m(\u001b[0m\u001b[0mh\u001b[0m\u001b[0;34m,\u001b[0m \u001b[0ma\u001b[0m\u001b[0;34m,\u001b[0m \u001b[0mv\u001b[0m\u001b[0;34m,\u001b[0m \u001b[0mg\u001b[0m\u001b[0;34m)\u001b[0m\u001b[0;34m:\u001b[0m\u001b[0;34m\u001b[0m\u001b[0;34m\u001b[0m\u001b[0m\n\u001b[0;32m----> 4\u001b[0;31m     \u001b[0mpredict\u001b[0m \u001b[0;34m=\u001b[0m \u001b[0maccidentModel\u001b[0m\u001b[0;34m.\u001b[0m\u001b[0mpredict_proba\u001b[0m\u001b[0;34m(\u001b[0m\u001b[0;34m[\u001b[0m\u001b[0;34m[\u001b[0m\u001b[0mh\u001b[0m\u001b[0;34m,\u001b[0m \u001b[0ma\u001b[0m\u001b[0;34m,\u001b[0m \u001b[0mv\u001b[0m\u001b[0;34m]\u001b[0m\u001b[0;34m]\u001b[0m\u001b[0;34m)\u001b[0m\u001b[0;34m[\u001b[0m\u001b[0;34m:\u001b[0m\u001b[0;34m,\u001b[0m \u001b[0mg\u001b[0m\u001b[0;34m]\u001b[0m\u001b[0;34m\u001b[0m\u001b[0;34m\u001b[0m\u001b[0m\n\u001b[0m\u001b[1;32m      5\u001b[0m     \u001b[0mmessage\u001b[0m \u001b[0;34m=\u001b[0m \u001b[0mpredict\u001b[0m\u001b[0;34m[\u001b[0m\u001b[0;36m0\u001b[0m\u001b[0;34m]\u001b[0m\u001b[0;34m\u001b[0m\u001b[0;34m\u001b[0m\u001b[0m\n\u001b[1;32m      6\u001b[0m     \u001b[0;32mreturn\u001b[0m \u001b[0mmessage\u001b[0m\u001b[0;34m\u001b[0m\u001b[0;34m\u001b[0m\u001b[0m\n",
                            "\u001b[0;32m~/opt/anaconda3/lib/python3.7/site-packages/sklearn/ensemble/_forest.py\u001b[0m in \u001b[0;36mpredict_proba\u001b[0;34m(self, X)\u001b[0m\n\u001b[1;32m    669\u001b[0m             \u001b[0mclasses\u001b[0m \u001b[0mcorresponds\u001b[0m \u001b[0mto\u001b[0m \u001b[0mthat\u001b[0m \u001b[0;32min\u001b[0m \u001b[0mthe\u001b[0m \u001b[0mattribute\u001b[0m \u001b[0;34m:\u001b[0m\u001b[0mterm\u001b[0m\u001b[0;34m:\u001b[0m\u001b[0;31m`\u001b[0m\u001b[0mclasses_\u001b[0m\u001b[0;31m`\u001b[0m\u001b[0;34m.\u001b[0m\u001b[0;34m\u001b[0m\u001b[0;34m\u001b[0m\u001b[0m\n\u001b[1;32m    670\u001b[0m         \"\"\"\n\u001b[0;32m--> 671\u001b[0;31m         \u001b[0mcheck_is_fitted\u001b[0m\u001b[0;34m(\u001b[0m\u001b[0mself\u001b[0m\u001b[0;34m)\u001b[0m\u001b[0;34m\u001b[0m\u001b[0;34m\u001b[0m\u001b[0m\n\u001b[0m\u001b[1;32m    672\u001b[0m         \u001b[0;31m# Check data\u001b[0m\u001b[0;34m\u001b[0m\u001b[0;34m\u001b[0m\u001b[0;34m\u001b[0m\u001b[0m\n\u001b[1;32m    673\u001b[0m         \u001b[0mX\u001b[0m \u001b[0;34m=\u001b[0m \u001b[0mself\u001b[0m\u001b[0;34m.\u001b[0m\u001b[0m_validate_X_predict\u001b[0m\u001b[0;34m(\u001b[0m\u001b[0mX\u001b[0m\u001b[0;34m)\u001b[0m\u001b[0;34m\u001b[0m\u001b[0;34m\u001b[0m\u001b[0m\n",
                            "\u001b[0;32m~/opt/anaconda3/lib/python3.7/site-packages/sklearn/utils/validation.py\u001b[0m in \u001b[0;36minner_f\u001b[0;34m(*args, **kwargs)\u001b[0m\n\u001b[1;32m     71\u001b[0m                           FutureWarning)\n\u001b[1;32m     72\u001b[0m         \u001b[0mkwargs\u001b[0m\u001b[0;34m.\u001b[0m\u001b[0mupdate\u001b[0m\u001b[0;34m(\u001b[0m\u001b[0;34m{\u001b[0m\u001b[0mk\u001b[0m\u001b[0;34m:\u001b[0m \u001b[0marg\u001b[0m \u001b[0;32mfor\u001b[0m \u001b[0mk\u001b[0m\u001b[0;34m,\u001b[0m \u001b[0marg\u001b[0m \u001b[0;32min\u001b[0m \u001b[0mzip\u001b[0m\u001b[0;34m(\u001b[0m\u001b[0msig\u001b[0m\u001b[0;34m.\u001b[0m\u001b[0mparameters\u001b[0m\u001b[0;34m,\u001b[0m \u001b[0margs\u001b[0m\u001b[0;34m)\u001b[0m\u001b[0;34m}\u001b[0m\u001b[0;34m)\u001b[0m\u001b[0;34m\u001b[0m\u001b[0;34m\u001b[0m\u001b[0m\n\u001b[0;32m---> 73\u001b[0;31m         \u001b[0;32mreturn\u001b[0m \u001b[0mf\u001b[0m\u001b[0;34m(\u001b[0m\u001b[0;34m**\u001b[0m\u001b[0mkwargs\u001b[0m\u001b[0;34m)\u001b[0m\u001b[0;34m\u001b[0m\u001b[0;34m\u001b[0m\u001b[0m\n\u001b[0m\u001b[1;32m     74\u001b[0m     \u001b[0;32mreturn\u001b[0m \u001b[0minner_f\u001b[0m\u001b[0;34m\u001b[0m\u001b[0;34m\u001b[0m\u001b[0m\n\u001b[1;32m     75\u001b[0m \u001b[0;34m\u001b[0m\u001b[0m\n",
                            "\u001b[0;32m~/opt/anaconda3/lib/python3.7/site-packages/sklearn/utils/validation.py\u001b[0m in \u001b[0;36mcheck_is_fitted\u001b[0;34m(estimator, attributes, msg, all_or_any)\u001b[0m\n\u001b[1;32m   1018\u001b[0m \u001b[0;34m\u001b[0m\u001b[0m\n\u001b[1;32m   1019\u001b[0m     \u001b[0;32mif\u001b[0m \u001b[0;32mnot\u001b[0m \u001b[0mattrs\u001b[0m\u001b[0;34m:\u001b[0m\u001b[0;34m\u001b[0m\u001b[0;34m\u001b[0m\u001b[0m\n\u001b[0;32m-> 1020\u001b[0;31m         \u001b[0;32mraise\u001b[0m \u001b[0mNotFittedError\u001b[0m\u001b[0;34m(\u001b[0m\u001b[0mmsg\u001b[0m \u001b[0;34m%\u001b[0m \u001b[0;34m{\u001b[0m\u001b[0;34m'name'\u001b[0m\u001b[0;34m:\u001b[0m \u001b[0mtype\u001b[0m\u001b[0;34m(\u001b[0m\u001b[0mestimator\u001b[0m\u001b[0;34m)\u001b[0m\u001b[0;34m.\u001b[0m\u001b[0m__name__\u001b[0m\u001b[0;34m}\u001b[0m\u001b[0;34m)\u001b[0m\u001b[0;34m\u001b[0m\u001b[0;34m\u001b[0m\u001b[0m\n\u001b[0m\u001b[1;32m   1021\u001b[0m \u001b[0;34m\u001b[0m\u001b[0m\n\u001b[1;32m   1022\u001b[0m \u001b[0;34m\u001b[0m\u001b[0m\n",
                            "\u001b[0;31mNotFittedError\u001b[0m: This RandomForestClassifier instance is not fitted yet. Call 'fit' with appropriate arguments before using this estimator."
                        ]
                    },
                    {
                        "output_type": "error",
                        "ename": "NotFittedError",
                        "evalue": "This RandomForestClassifier instance is not fitted yet. Call 'fit' with appropriate arguments before using this estimator.",
                        "traceback": [
                            "\u001b[0;31m---------------------------------------------------------------------------\u001b[0m",
                            "\u001b[0;31mNotFittedError\u001b[0m                            Traceback (most recent call last)",
                            "\u001b[0;32m<ipython-input-26-83befdc64328>\u001b[0m in \u001b[0;36mon_button_clicked\u001b[0;34m(b)\u001b[0m\n\u001b[1;32m     67\u001b[0m     \u001b[0;32mwith\u001b[0m \u001b[0moutput\u001b[0m\u001b[0;34m:\u001b[0m\u001b[0;34m\u001b[0m\u001b[0;34m\u001b[0m\u001b[0m\n\u001b[1;32m     68\u001b[0m \u001b[0;34m\u001b[0m\u001b[0m\n\u001b[0;32m---> 69\u001b[0;31m         \u001b[0mresult\u001b[0m \u001b[0;34m=\u001b[0m \u001b[0mpredictSeverity\u001b[0m\u001b[0;34m(\u001b[0m\u001b[0mhitobject\u001b[0m\u001b[0;34m.\u001b[0m\u001b[0mvalue\u001b[0m\u001b[0;34m,\u001b[0m \u001b[0mage\u001b[0m\u001b[0;34m.\u001b[0m\u001b[0mvalue\u001b[0m\u001b[0;34m,\u001b[0m \u001b[0mcar\u001b[0m\u001b[0;34m.\u001b[0m\u001b[0mvalue\u001b[0m\u001b[0;34m,\u001b[0m \u001b[0mgender\u001b[0m\u001b[0;34m.\u001b[0m\u001b[0mvalue\u001b[0m\u001b[0;34m)\u001b[0m\u001b[0;34m\u001b[0m\u001b[0;34m\u001b[0m\u001b[0m\n\u001b[0m\u001b[1;32m     70\u001b[0m         \u001b[0mpercentage\u001b[0m \u001b[0;34m=\u001b[0m \u001b[0mfloat\u001b[0m\u001b[0;34m(\u001b[0m\u001b[0mresult\u001b[0m\u001b[0;34m)\u001b[0m \u001b[0;34m*\u001b[0m \u001b[0;36m100\u001b[0m\u001b[0;34m\u001b[0m\u001b[0;34m\u001b[0m\u001b[0m\n\u001b[1;32m     71\u001b[0m         \u001b[0mprint\u001b[0m\u001b[0;34m(\u001b[0m\u001b[0;34m\"{:.2f}\"\u001b[0m\u001b[0;34m.\u001b[0m\u001b[0mformat\u001b[0m\u001b[0;34m(\u001b[0m\u001b[0mpercentage\u001b[0m\u001b[0;34m)\u001b[0m\u001b[0;34m)\u001b[0m\u001b[0;34m\u001b[0m\u001b[0;34m\u001b[0m\u001b[0m\n",
                            "\u001b[0;32m<ipython-input-25-336dac09e3cb>\u001b[0m in \u001b[0;36mpredictSeverity\u001b[0;34m(h, a, v, g)\u001b[0m\n\u001b[1;32m      2\u001b[0m \u001b[0;31m#The dicts from before will now be used.\u001b[0m\u001b[0;34m\u001b[0m\u001b[0;34m\u001b[0m\u001b[0;34m\u001b[0m\u001b[0m\n\u001b[1;32m      3\u001b[0m \u001b[0;32mdef\u001b[0m \u001b[0mpredictSeverity\u001b[0m \u001b[0;34m(\u001b[0m\u001b[0mh\u001b[0m\u001b[0;34m,\u001b[0m \u001b[0ma\u001b[0m\u001b[0;34m,\u001b[0m \u001b[0mv\u001b[0m\u001b[0;34m,\u001b[0m \u001b[0mg\u001b[0m\u001b[0;34m)\u001b[0m\u001b[0;34m:\u001b[0m\u001b[0;34m\u001b[0m\u001b[0;34m\u001b[0m\u001b[0m\n\u001b[0;32m----> 4\u001b[0;31m     \u001b[0mpredict\u001b[0m \u001b[0;34m=\u001b[0m \u001b[0maccidentModel\u001b[0m\u001b[0;34m.\u001b[0m\u001b[0mpredict_proba\u001b[0m\u001b[0;34m(\u001b[0m\u001b[0;34m[\u001b[0m\u001b[0;34m[\u001b[0m\u001b[0mh\u001b[0m\u001b[0;34m,\u001b[0m \u001b[0ma\u001b[0m\u001b[0;34m,\u001b[0m \u001b[0mv\u001b[0m\u001b[0;34m]\u001b[0m\u001b[0;34m]\u001b[0m\u001b[0;34m)\u001b[0m\u001b[0;34m[\u001b[0m\u001b[0;34m:\u001b[0m\u001b[0;34m,\u001b[0m \u001b[0mg\u001b[0m\u001b[0;34m]\u001b[0m\u001b[0;34m\u001b[0m\u001b[0;34m\u001b[0m\u001b[0m\n\u001b[0m\u001b[1;32m      5\u001b[0m     \u001b[0mmessage\u001b[0m \u001b[0;34m=\u001b[0m \u001b[0mpredict\u001b[0m\u001b[0;34m[\u001b[0m\u001b[0;36m0\u001b[0m\u001b[0;34m]\u001b[0m\u001b[0;34m\u001b[0m\u001b[0;34m\u001b[0m\u001b[0m\n\u001b[1;32m      6\u001b[0m     \u001b[0;32mreturn\u001b[0m \u001b[0mmessage\u001b[0m\u001b[0;34m\u001b[0m\u001b[0;34m\u001b[0m\u001b[0m\n",
                            "\u001b[0;32m~/opt/anaconda3/lib/python3.7/site-packages/sklearn/ensemble/_forest.py\u001b[0m in \u001b[0;36mpredict_proba\u001b[0;34m(self, X)\u001b[0m\n\u001b[1;32m    669\u001b[0m             \u001b[0mclasses\u001b[0m \u001b[0mcorresponds\u001b[0m \u001b[0mto\u001b[0m \u001b[0mthat\u001b[0m \u001b[0;32min\u001b[0m \u001b[0mthe\u001b[0m \u001b[0mattribute\u001b[0m \u001b[0;34m:\u001b[0m\u001b[0mterm\u001b[0m\u001b[0;34m:\u001b[0m\u001b[0;31m`\u001b[0m\u001b[0mclasses_\u001b[0m\u001b[0;31m`\u001b[0m\u001b[0;34m.\u001b[0m\u001b[0;34m\u001b[0m\u001b[0;34m\u001b[0m\u001b[0m\n\u001b[1;32m    670\u001b[0m         \"\"\"\n\u001b[0;32m--> 671\u001b[0;31m         \u001b[0mcheck_is_fitted\u001b[0m\u001b[0;34m(\u001b[0m\u001b[0mself\u001b[0m\u001b[0;34m)\u001b[0m\u001b[0;34m\u001b[0m\u001b[0;34m\u001b[0m\u001b[0m\n\u001b[0m\u001b[1;32m    672\u001b[0m         \u001b[0;31m# Check data\u001b[0m\u001b[0;34m\u001b[0m\u001b[0;34m\u001b[0m\u001b[0;34m\u001b[0m\u001b[0m\n\u001b[1;32m    673\u001b[0m         \u001b[0mX\u001b[0m \u001b[0;34m=\u001b[0m \u001b[0mself\u001b[0m\u001b[0;34m.\u001b[0m\u001b[0m_validate_X_predict\u001b[0m\u001b[0;34m(\u001b[0m\u001b[0mX\u001b[0m\u001b[0;34m)\u001b[0m\u001b[0;34m\u001b[0m\u001b[0;34m\u001b[0m\u001b[0m\n",
                            "\u001b[0;32m~/opt/anaconda3/lib/python3.7/site-packages/sklearn/utils/validation.py\u001b[0m in \u001b[0;36minner_f\u001b[0;34m(*args, **kwargs)\u001b[0m\n\u001b[1;32m     71\u001b[0m                           FutureWarning)\n\u001b[1;32m     72\u001b[0m         \u001b[0mkwargs\u001b[0m\u001b[0;34m.\u001b[0m\u001b[0mupdate\u001b[0m\u001b[0;34m(\u001b[0m\u001b[0;34m{\u001b[0m\u001b[0mk\u001b[0m\u001b[0;34m:\u001b[0m \u001b[0marg\u001b[0m \u001b[0;32mfor\u001b[0m \u001b[0mk\u001b[0m\u001b[0;34m,\u001b[0m \u001b[0marg\u001b[0m \u001b[0;32min\u001b[0m \u001b[0mzip\u001b[0m\u001b[0;34m(\u001b[0m\u001b[0msig\u001b[0m\u001b[0;34m.\u001b[0m\u001b[0mparameters\u001b[0m\u001b[0;34m,\u001b[0m \u001b[0margs\u001b[0m\u001b[0;34m)\u001b[0m\u001b[0;34m}\u001b[0m\u001b[0;34m)\u001b[0m\u001b[0;34m\u001b[0m\u001b[0;34m\u001b[0m\u001b[0m\n\u001b[0;32m---> 73\u001b[0;31m         \u001b[0;32mreturn\u001b[0m \u001b[0mf\u001b[0m\u001b[0;34m(\u001b[0m\u001b[0;34m**\u001b[0m\u001b[0mkwargs\u001b[0m\u001b[0;34m)\u001b[0m\u001b[0;34m\u001b[0m\u001b[0;34m\u001b[0m\u001b[0m\n\u001b[0m\u001b[1;32m     74\u001b[0m     \u001b[0;32mreturn\u001b[0m \u001b[0minner_f\u001b[0m\u001b[0;34m\u001b[0m\u001b[0;34m\u001b[0m\u001b[0m\n\u001b[1;32m     75\u001b[0m \u001b[0;34m\u001b[0m\u001b[0m\n",
                            "\u001b[0;32m~/opt/anaconda3/lib/python3.7/site-packages/sklearn/utils/validation.py\u001b[0m in \u001b[0;36mcheck_is_fitted\u001b[0;34m(estimator, attributes, msg, all_or_any)\u001b[0m\n\u001b[1;32m   1018\u001b[0m \u001b[0;34m\u001b[0m\u001b[0m\n\u001b[1;32m   1019\u001b[0m     \u001b[0;32mif\u001b[0m \u001b[0;32mnot\u001b[0m \u001b[0mattrs\u001b[0m\u001b[0;34m:\u001b[0m\u001b[0;34m\u001b[0m\u001b[0;34m\u001b[0m\u001b[0m\n\u001b[0;32m-> 1020\u001b[0;31m         \u001b[0;32mraise\u001b[0m \u001b[0mNotFittedError\u001b[0m\u001b[0;34m(\u001b[0m\u001b[0mmsg\u001b[0m \u001b[0;34m%\u001b[0m \u001b[0;34m{\u001b[0m\u001b[0;34m'name'\u001b[0m\u001b[0;34m:\u001b[0m \u001b[0mtype\u001b[0m\u001b[0;34m(\u001b[0m\u001b[0mestimator\u001b[0m\u001b[0;34m)\u001b[0m\u001b[0;34m.\u001b[0m\u001b[0m__name__\u001b[0m\u001b[0;34m}\u001b[0m\u001b[0;34m)\u001b[0m\u001b[0;34m\u001b[0m\u001b[0;34m\u001b[0m\u001b[0m\n\u001b[0m\u001b[1;32m   1021\u001b[0m \u001b[0;34m\u001b[0m\u001b[0m\n\u001b[1;32m   1022\u001b[0m \u001b[0;34m\u001b[0m\u001b[0m\n",
                            "\u001b[0;31mNotFittedError\u001b[0m: This RandomForestClassifier instance is not fitted yet. Call 'fit' with appropriate arguments before using this estimator."
                        ]
                    }
                ]
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
    "model_id": "860f5d8870f04ce58b3e5976cd9ee9e8"
}
</script>

<script type="application/vnd.jupyter.widget-view+json">
{
    "version_major": 2,
    "version_minor": 0,
    "model_id": "4fc87ab0cf2f45e3addda616832718dc"
}
</script>

<script type="application/vnd.jupyter.widget-view+json">
{
    "version_major": 2,
    "version_minor": 0,
    "model_id": "e2b0c0a85252422a9a24bfc083f16214"
}
</script>

<script type="application/vnd.jupyter.widget-view+json">
{
    "version_major": 2,
    "version_minor": 0,
    "model_id": "87e3722bb5024d2d82e46b2e5ba40de4"
}
</script>

<script type="application/vnd.jupyter.widget-view+json">
{
    "version_major": 2,
    "version_minor": 0,
    "model_id": "8c55868dfd164456929f188862dae2ec"
}
</script>

<script type="application/vnd.jupyter.widget-view+json">
{
    "version_major": 2,
    "version_minor": 0,
    "model_id": "318e99592eae46f6806214fdc46e45f9"
}
</script>

</body>
</html>

So apparently it is going to work that is the main factor. Can we by that conclude that the women in UK doesn't work? Knowing some few facts about UK (such as a daycare spot cost app. 800 Pounds a month it is not unrealistic that there is a majority of the men working - source is from several british friends) However it is not concluded that women doesn't work and hence the men are contributing with all the accidents

For a more secure walk through you will be able to see in our notebook which streetcorneers to avoid. 

Lastly you could also just consider going on really slow or really fast?

<iframe id="inlineFrameExample"
    title="Inline Frame Example"
    width="1000"
    height="500"
    src="hhttps://severin.edea.dk/SD/slow.pngg">
</iframe>

Looking to the different aspects of these stats it is safe to conclude that London is a city with a lot of accidents. Some streets are safer than others and if you are a newbie to the traffic - avoid the clusters ...

# Drive safe
