# question
research question: what are the factors influencing the extent of economic agglomeration?
There are many reasons why it is interesting to know why agglomerations exist. From transport costs and concentration of supply and demand of goods and services, to soaring real estate prices in central cities.

# method
In our attempt to answer the question, we rely on the model described by Pflüger (which you can read for free [here](http://www.diw.de/documents/publikationen/73/diw_01.c.40255.de/dp339.pdf))

The model by Pflüger provides a basic understanding of the factors influencing to what extent agglomeration takes place in a space consisting of two citites and their hinterland. However, even the basic model is not easily analised because of the complex equation with which Pflüger concludes. To make this model completely accessible, we use python to present the main equation in a graph, which is also used by Pflüger to illustrate his model, and we add the possibility of adjusting all variables at will using sliders. 

The graph below is based on the following equation:

$V-V^{*}=\frac{\xi}{\sigma-1}*ln\left(\frac{h+\varphi(1-h)}{1-h+\varphi h}\right) + \frac{\xi (1-\varphi)}{\sigma}\left [ \frac{\rho+h}{h+\varphi(1-h)}-\frac{\rho^{*}+1-h}{1-h+\varphi h} \right ]$

Where $V-V^{*}$ is the difference between the value of establishing a business in the one location versus in the other. This is what all the sources of agglomeration boil down to: if the value of establishing "at home"($V$) is bigger than that of establishing "abroad"($V^{*}$), there will be businesses moving to the "home" location untill balance is restored. Any equilibrium is therefore located either on a point where $V^{*}-V=0$, **or** when all businesses are located at one of the locations. The vertical axis indicates the extent of agglomeration, indicated by the percentage of businesses located in the "home" location. Note that agglomeration can also take place abroad, in this case the percentage of businesses located at home will be below 0.5. Since there is no outside location, the other businesses will be located in the other location. 



# assumption
verschil in bevolking tussen twee regios is exogeen (grootendeels)
