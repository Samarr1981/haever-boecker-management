# Haver & Boecker Machinery Schedules Integration Project

My role: Backend architecture on a four-developer team. Designed the data model and API layer, built the Entity Framework Core schema, and wrote the SQL for orders, machines, vendors, purchase orders, and delivery tracking. Team worked in sprints with daily standups and retrospectives. This repo is a single squashed push of the team's final build, not per-developer commit history.

## Overview

The **Haver & Boecker Machinery Schedules Integration Project** is designed to streamline the process of managing and tracking machinery schedules by integrating data from two separate Excel spreadsheets maintained by the Operations and Project Management departments. The goal is to create a unified, printable schedule for machinery (vibrating screens) that tracks various milestones, including order information, engineering milestones, procurement, assembly, testing, and delivery.

This system enables better tracking, scheduling, and communication across teams, ensuring timely deliveries and improved internal processes.

## Features

- **Unified Data Model**: Merges two separate Excel files into a single cohesive schedule.
- **Sales Order Integration**: Track sales order details, including customer information and related machines.
- **Gantt Chart Visualization**: Display engineering milestones, procurement details, assembly, testing, and delivery dates.
- **Machine Tracking**: Maintain machine records, including production details, serial numbers, and status.
- **Vendor Management**: Track vendor information, purchase orders, and delivery dates.
- **Notes Management**: Keep detailed notes on each machine and order.
- **Reporting & Printability**: Generate printable schedules with detailed data for all orders and machines.

## Technologies Used

- **C#**
- **ASP.NET Core MVC**
- **SQLite**
- **Frappe Gantt** (for Gantt Chart Visualization)
- **HTML, CSS** (for frontend styling)
- **Entity Framework Core** (for database handling)
- **Visual Studio** (IDE for development)

