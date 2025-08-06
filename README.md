# IoT Quality Assessment Framework

 

This repository contains a validated, context-aware framework for evaluating the quality of IoT systems across multiple operational domains. It integrates simulation data, machine learning, and statistical analysis to assess service-level performance in both synthetic and real-world environments.

 

 

## 🌐 Domains Covered

 

- Device-level performance

- Network behavior

- Environmental monitoring

- Sensor data integrity

- Service delivery quality

 

 

## 📁 Project Structure

 

iot-quality-framework/

│

├── Smart Agriculture Simulation/

│   ├── quality_agriculture.py

│   ├── data/

│   └── results/

│

├── Smart Industrial Quality Evaluation/

│   ├── quality_industrial.py

│   ├── data/

│   └── results/

│

├── DOC/

│   ├── methodology.md

│   ├── overview.md

│   └── references.md

│

├── main.py

├── README.md

├── CHANGELOG.md

├── LICENSE

└──.gitignore

```

 

---

 

## 🚀 How to Run

 

Make sure you have Python 3.x and the required libraries installed.

 

bash

pip install -r Smart Agriculture Simulation/requirements.txt

pip install -r Smart Industrial Quality Evaluation/requirements.txt

 

Then run the main script:

 

bash

python main.py

 

Results will be saved in the respective `results/` folders.

 

 

## 📊 Evaluation Summary

 

- Smart Agriculture Simulation

  Quality improved by 16% using weighted indicators

  p = 0.0003, Cohen’s d = 1.84

 

- Smart Industrial Evaluation

  Quality improved by 12% using weighted indicators

  p = 0.00001, Cohen’s d = 1.76

 

 

## 📚 Documentation

 

- [`DOC/methodology.md`](DOC/methodology.md): Analytical process

- [`DOC/overview.md`](DOC/overview.md): Project summary

- [`DOC/references.md`](DOC/references.md): Source materials

 

 

## 🐳 Docker Support

 

A Docker image is available for quick deployment:

 

 

docker pull iot-quality-eval:v1.0

 

 

## 📄 License

 

This project is licensed under the terms of the [MIT License](LICENSE).

 

 

## 🤝 Acknowledgments

 

This framework builds upon a structured review of 83 peer-reviewed sources and is empirically validated using both synthetic and real-world datasets. Special thanks to the authors of the original study:

**Naem, Koudil, Yousif, and Ouldimam**

 

 

## 🔗 Repository

 

GitHub: [github.com/mnaem/iot-quality-framework](https://github.com/mnaem/iot-quality-framework)

 

