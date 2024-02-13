# Valore

**Valore** is a pioneering financial and economic modeling software designed to transform the traditional finance operations in the oil, gas, natural resources, and energy industries. Built with the intent to surpass the limitations of conventional tools like Excel, Valore introduces a high-precision, real-time modeling solution capable of handling complex project components and computations at an unprecedented scale.

## Introduction

The finance teams across various sectors, including natural resources, industrials, energy, and healthcare, have long relied on outdated technologies that, despite their potential for creative use, fall short in terms of precision and efficiency for projects with numerous components. Valore is developed to showcase the immense capabilities of modern software in financial modeling, aiming to unlock new possibilities for software-powered business solutions in these industries.

## The Problem

Traditional financial modeling, especially in energy and natural resources projects, involves cumbersome processes that start with a production curve and extend to gathering operational details, legalities, cost assumptions, and much more. Analysts are forced to rely on overly simplified or numerous complex models that cannot adapt to the dynamic nature of project operations, leading to inaccurate forecasting and decision-making.

## The Solution: Valore

Valore revolutionizes this approach by offering a scalable, precise, and real-time financial modeling tool. It allows for the creation of detailed, customizable financial models for every production well and project component, leveraging the strengths of object-oriented programming and the powerful vectoral operations of Python libraries.

### Tech Stack

- **Frontend**: React, Vite, CSS, Material UI, React Router
- **Backend**: Python, Flask, RESTful API
- **Database**: PostgreSQL, SQLAlchemy
- **Data Visualization**: ChartJs
- **Financial Modeling**: Pandas, Numpy
- **Deployment**: Render (Cloud-based)

### Features

#### Create a Well
- Upload a type curve .csv file for individual well analysis, addition to projects, or as a project's initial well. Files must include months, total oil, and gas production data.

#### Gas Composition Assumptions
- Input detailed gas composition for modeling potential products like NGLs and Helium.

#### Start Dates
- Assign unique production start dates for each well to precisely plan costs and cash flows.

#### Operation Assumptions
- Detailed modeling for Working Interest, Net Revenue Interest, costs, taxes, and expenditures for individual or thousands of wells in a project.

#### Select a Well
- Toggle selection to display or edit assumptions and statistics for a specific well.

#### Dashboard-Well
- View single well summary statistics and economics, including ROI, IRR, NPV10 metrics, revenues, production figures, and more.

#### Project Level Summary
- Aggregate project statistics and economics, showcasing ROI, IRR, NPV10 metrics, total revenues, and monthly financials.
