# IoT Cloud Monitoring System — Kelompok 15

Real-time temperature and humidity monitoring system built on Microsoft Azure as the final project for Cloud Computing course, Universitas Palangka Raya.

## Architecture

- **Device Layer**: Wokwi IoT simulator replicating DHT22 sensor (ESP32)
- **Compute Layer**: Azure Virtual Machine (Ubuntu Server) running Python Flask
- **Storage Layer**: Azure Database for MySQL (structured data) + Azure Blob Storage (raw JSON payloads)
- **Monitoring**: Azure Monitor, Log Analytics Workspace, Microsoft Defender for Cloud
- **Infrastructure**: Provisioned via Terraform (IaC)

## Stack

`Python` `Flask` `MySQL` `Microsoft Azure` `Terraform` `Wokwi`

## Live Dashboard

`http://20.24.211.104:5000/`

## Wokwi Simulation
https://wokwi.com/projects/463469377900641281

## Team

| Name | NIM |
|---|---|
| Agung Setyo Pambudi | 2330205030060 |
| Muhamad Rafliansyah | 2330205030043 |
| Septio Praja | 2330205030045 |
