# Liferay Forms Autosave Fragment

![Gif of Use](https://media.giphy.com/media/1AfITT7a6wBMoJmnEn/giphy.gif)

This fragment modifies the existing autosave behavior in Liferay 7.1 Forms by having it save whenever the form changes instead of only once every 60 seconds. The request to save the form is debounced and it works for all field types. I hope you enjoy it.

Liferay fragments must point towards a specific module and version in order to be applied. You will likely have to modify this before deploying. It can be modified [here](https://github.com/ethib137/form-autosave-fragment/blob/master/bnd.bnd#L4).

In order to handle the translation of the saving status you will also need to deploy a resource bundle for each language you want to support. I have created resources bundles for [base language](https://github.com/ethib137/form-autosave-resource-bundle), [english](https://github.com/ethib137/form-autosave-en-resource-bundle), [french](https://github.com/ethib137/form-autosave-fr-resource-bundle), and [arabic](https://github.com/ethib137/form-autosave-ar-resource-bundle). If you need another language it shouldn't be too hard to modify one of those to suit your needs. 

I hope you enjoy it.
