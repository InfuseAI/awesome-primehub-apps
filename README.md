# 🏎️ Awesome PrimeHub Apps

This repo collects awesome PrimeHub application templates.

## 📘 What is PrimeHub App

PrimeHub aims at being a MLOps platform where scientists can orchestrate data/tools for the acceleration of researches. In terms of a platform, we introduce PrimeHub Apps that PrimeHub capability is able to be extended by integrations of 3rd-party applications such as auto ML tools, visualization tools, etc. These integrated applications also benefit from access-control and resource constraints of PrimeHub. [[Read more]](https://docs.primehub.io/docs/primehub-app)

## ⚙️ Installation

There should be pre-installed apps in your PrimeHub.

If you'd like to import any PrimeHub App that you don't have, there are two ways to do so:

1. Import the YAML file using `kubectl`
    ```
    $ kubectl apply -f [YAML URL]
    ```

2. Import the YAML from PrimeHub console admin portal.

## 🖌️ Create Your Own PrimeHub App

Create a PrimeHub app is easy. First, you have to containerize your application, and then it's as simple as describing a Kubernetes pod with some limitations.

Please head to our [documentation site](https://docs.primehub.io/docs/primehub-app-tutorial-template) for detailed information and system design.

## 🎉 Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please specify in your PR if you want your PrimeHub app pre-installed with PrimeHub or not.

## 👾 License
[Apache 2.0](https://www.apache.org/licenses/LICENSE-2.0)
