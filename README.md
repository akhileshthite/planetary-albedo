# Machine Learning Model for the Planetary Albedo

NASA's Lunar Prospector orbited the Moon for almost 19 months to map its surface composition and to look for polar ice. The probe found evidence suggesting water ice at both poles. The mission ended with the spacecraft impacting the lunar surface, creating a dust cloud that was studied from Earth.

NASA’s MESSENGER spacecraft orbited Mercury from 2011 to 2015 (for almost 4 years). The mission determined Mercury’s surface composition, revealed its geological history, discovered details about its internal magnetic field, and verified its polar deposits are dominantly water-ice. 

Planetary surfaces are observed as all electromagnetic wavelengths (e.g. radar, infrared, optical, ultraviolet, x-ray, gamma-ray), and each wavelength provides unique information about the chemistry, mineralogy, and history of the surface. Yet the information is not entirely independent. For example, the chemical element iron, which is mapped with x-rays and gamma rays, is highly related to optical albedo on the Moon. Knowing this, we can develop high-spatial resolution predictive maps of iron based on optical data. On other planets, the relationships between the observations are less well known, and indeed some datasets are missing.

The goal of the project is to use machine learning techniques to identify relationships between planetary mapped datasets, with the goal of providing deeper understanding of planetary surfaces and to have predictive power for planetary surfaces with incomplete datasets.

## Goals
Currently I've trained both the models on less number of n_estimators because of longer time consumption. My further goal is to improve the accuracy of both models.
