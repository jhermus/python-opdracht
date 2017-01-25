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

# Results

## Effects of transportation costs ($\tau$)
In this model transportation costs are a spreading force, i.e. if transportation costs go up there
will be less agglomeration. The reason for this is that it is more profitable for firms to locate
close to the immobile consumers when the transportation costs are high. Since the price of the
goods imported from the other region is dependent on the transportation costs the average
price will increase with transportation costs. It’s also less relevant for the home region how
many firms are located in the abroad region since the transportation costs makes them less
competitive with the home region. A higher transportation costs reduces the earnings of
entrepreneurs. 

## Effects of a stronger taste for variety ($\sigma$)
When consumers have a stronger taste for variety this leads to agglomeration. The
effect is basically the opposite of the effect by higher transportation costs. It makes
it easier to export to other regions and increases the earnings for entrepreneurs. It
raises the prices in both the home and foreign region. Since the consumers want
more variety and are willing to pay more for it there is no reason for the firms to
locate closer to the immobile consumers. 

## Effect of a lower ratio of immobile to mobile workers ($\rho$) in the economy.
If there are less immobile workers, the demand market is bigger where most firms are
located. Entrepreneurs, which are mobile, make up more of the demand market if the ratio
of immobile to mobile workers goes down. Firms would rather locate where most customers
are located because you have a transport cost to customers in the other region, and would
like to minimise this amount of customers. When the ratio goes down, there are less of these
immobile customers, to which you have to charge a transportation cost, left in the region in
which you do not locate, and most of your customer base will move to the region with the
most firms, where you also locate. Therefore firms will agglomerate more, the more the ratio
of immobile to mobile workers decreases.

# Discussion

The Pfluger model we presented is a simple model and it is easy to see what happens if different parameters are changed. The model has however some limitations. Not all agglomeration costs are included in the model. In the model agglomeration in one city means that in the other city prices will be higher. This will lead to more firms moving to this city because profits are higher. Another cost of agglomeration is however not included. If more people concentrate congestion and pollution will become a problem. Furthermore housing prices will increase, this happened for example in San Francisco where house prices have increased as a consequence of companies concentrating in Sillicon Valley.

# references
<a name="abcd"></a>

[A. Ciccone and R. E. Hall (1996). Productivity and the density of economic activity, *American
Economic Review*, 86, 54 70 .](https://web.stanford.edu/~rehall/Productivity-AER-March-1996.pdf)

[J. V. Henderson (1986). Efficiency of resource usage and city size, *Journal of Urban Economics*, 19,
47 70 .](http://www.gonzalo.depeco.econo.unlp.edu.ar/EU1UTDT/henderson86.pdf)

[R. L. Moomaw (1981). Productivity and city size: A critique of the evidence, *Quarterly Journal of
Economics*, 96, 675 688 . Ž .](http://qje.oxfordjournals.org/content/96/4/675.short)

[R. Nakamura (1985). Agglomeration economies in urban manufacturing industries: A case of Japanese
cities, *Journal of Urban Economics*, 17, 108 124 .](http://www.sciencedirect.com/science/article/pii/0094119085900403)

[M. Pflüger (2004). A simple, analytically solvable, Chamberlinian agglomeration model. *Regional Science and Urban Economics*, 34(5), 565-573.](http://www.diw.de/documents/publikationen/73/diw_01.c.40255.de/dp339.pdf)

[L. Sveikauskas (1975). The productivity of cities, *Quarterly Journal of Economics*, 89, 393 413
Ž . ](http://www.jstor.org/stable/pdf/1885259.pdf)
