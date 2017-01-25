|name|ANR|email|
|----|---|-----|
|Joep Hermus|568638|j.hermus@tilburguniversity.edu|
|Freek Heuvelmans|702516|f.j.heuvelmans@tilburguniversity.edu|

# question
research question: what are the factors influencing the extent of economic agglomeration?
There are many reasons why it is interesting to know why agglomerations exist. From transport costs and concentration of supply and demand of goods and services, to soaring real estate prices in central cities. Last but not least, a good amount of studies has found that the concentration of economic activity results in higher productivity and more economic growth [(Ciccone & Hall, 1996; Henderson, 1986; Nakamura, 1985; Moomaw, 1981; Sveikauskas, 1975)](#abcd).

# method
In our attempt to answer the question, we rely on the model described by Pflüger (which you can read for free [here](http://www.diw.de/documents/publikationen/73/diw_01.c.40255.de/dp339.pdf))

The model by Pflüger provides a basic understanding of the factors influencing to what extent agglomeration takes place in a space consisting of two citites and their hinterland. However, even the basic model is not easily analised because of the complex equation with which Pflüger concludes. To make this model completely accessible, we use python to present the main equation in a graph, which is also used by Pflüger to illustrate his model, and we add the possibility of adjusting all variables at will using sliders. 

The graph below is based on the following equation:

$V-V^{*}=\frac{\xi}{\sigma-1}*ln\left(\frac{h+\varphi(1-h)}{1-h+\varphi h}\right) + \frac{\xi (1-\varphi)}{\sigma}\left [ \frac{\rho+h}{h+\varphi(1-h)}-\frac{\rho^{*}+1-h}{1-h+\varphi h} \right ]$

Where $V-V^{*}$ is the difference between the value of establishing a business in the one location versus in the other. This is what all the sources of agglomeration boil down to: if the value of establishing "at home"($V$) is bigger than that of establishing "abroad"($V^{*}$), there will be businesses moving to the "home" location untill balance is restored. Any equilibrium is therefore located either on a point where $V^{*}-V=0$, **or** when all businesses are located at one of the locations. The vertical axis indicates the extent of agglomeration, indicated by the percentage of businesses located in the "home" location. Note that agglomeration can also take place abroad, in this case the percentage of businesses located at home will be below 0.5. Since there is no outside location, the other businesses will be located in the other location. 



|Symbol|Definition|
|----|---|
|$\tau$|transport costs|
|$\sigma$|elasticity of substitution between manufacturing varieties|
|$\phi$ $=\tau^{1-\sigma}$|freeness of trade|
|$h$|share of total skilled labor supply that works in home region|
|$\rho$|share of labour to human capital owners/share of immobile to mobile workers|
|$\xi$|preference for manufactured goods|

​


# assumption
verschil in bevolking tussen twee regios is exogeen (grootendeels)

# Discussion

The Pfluger model we presented is a simple model and it is easy to see what happens if different parameters are changed. The model has however some limitations. Not all agglomeration costs are included in the model. In the model agglomeration in one city means that in the other city prices will be higher. This will lead to more firms moving to this city because profits are higher. Another cost of agglomeration is however not included. If more people concentrate congestion and pollution will become a problem. Furthermore housing prices will increase, this happened for example in San Francisco where house prices have increased as a consequence of companies concentrating in Sillicon Valley.

## references
<a name="abcd"></a>

A. Ciccone and R. E. Hall (1996). Productivity and the density of economic activity, *American
Economic Review*, 86, 54 70 .

J. V. Henderson (1986). Efficiency of resource usage and city size, *Journal of Urban Economics*, 19,
47 70 .

R. L. Moomaw (1981). Productivity and city size: A critique of the evidence, *Quarterly Journal of
Economics*, 96, 675 688 . Ž .

R. Nakamura (1985). Agglomeration economies in urban manufacturing industries: A case of Japanese
cities, *Journal of Urban Economics*, 17, 108 124 .

M. Pflüger (2004). A simple, analytically solvable, Chamberlinian agglomeration model. *Regional Science and Urban Economics*, 34(5), 565-573.

L. Sveikauskas (1975). The productivity of cities, *Quarterly Journal of Economics*, 89, 393 413
Ž . 
