# Surrogate-based-inverse-design-of-bending-induced-bistable-metamaterials
Bistable structural units that can reversibly snap between two stable configurations are promising for applications in shape morphing and energy absorption. However, determining suitable unit-cell geometries for a prescribed target response remains challenging.

In this work, we develop a surrogate-based inverse design framework for a bending-induced bistable metamaterial unit, built on a pre-established theoretical analytical model.

We first perform a parameter sweep in a dimensionless design space using the analytical model and extract eight scalar descriptors and a curve-type label from the normalized moment–rotation response.
A forward surrogate model is then trained to map geometric parameters to these curve descriptors and curve type.
Next, we compare two inverse strategies: a direct inverse network and a cycle-consistent inverse network coupled with the forward model.

The results show that both inverse models recover the geometric parameters with an average relative error of about 5–8% and generate moment–rotation curves that closely match the analytical model. The cycle-consistent inverse network achieves slightly higher accuracy in reproducing the target curves than the direct inverse model, demonstrating the feasibility of fast surrogate-based inverse design.
