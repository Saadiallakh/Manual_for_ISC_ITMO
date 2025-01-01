# Follow the link to download the Manual
https://books.ifmo.ru/book/2745/Practice-Oriented_Introduction_to_Machine_Learning_:_Linear_Regression%2C_Decision_Tree%2C_and_Single_Layer_Perceptron_models_:_uchebno-metodicheskoe_posobie..htm 

# Cite the Manual 
Normatov S., Nesterov P.V., Aliev T.A., Timralieva A.A., Novikov A.S., Skorb E.V. Practice-Oriented Introduction to Machine Learning : Linear Regression, Decision Tree, and Single Layer Perceptron models : Учебно-методическое пособие. - Санкт-Петербург: Университет ИТМО, 2024. - 51 с. - экз.

# Dataset description

The data represents the energy values of supramolecular systems, calculated using two Quantum Chemical approximations. The "hf_" (Hartree-Fock) set was calculated using fast but inaccurate approximation, while "dft_" (Density Functional Theory) set was calculated using accurate yet time-consuming approximation.

Feature  | Type | Level of theory
-------------------|--------------------|--------------------
dft_gibbs_free_energy_ev       |Target| Gibbs free energy of the supramolecular system, calculated using the DFT
dft_electronic_energy_ev       |Target| Electronic energy of the supramolecular system, calculated using the DFT
dft_entropy_ev       |Target| Entropy of the supramolecular system, calculated using the DFT
dft_enthalpy_ev       |Target| Enthalpy of the supramolecular system, calculated using the DFT
hf_gibbs_free_energy_ev       |Training| Gibbs free energy of the supramolecular system, calculated using the HF
hf_electronic_energy_ev       |Training| Electronic energy of the supramolecular system, calculated using the HF
hf_entropy_ev       |Training| Entropy of the supramolecular system, calculated using the HF
hf_enthalpy_ev       |Training| Enthalpy of the supramolecular system, calculated using the HF

![User Interface](graphical_abstract.png)
