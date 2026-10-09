# Lab 35 — Plan the API Service

## Provide HttpClient

Inject HttpClient in the constructor; ensure HttpClientModule is imported at the app module boundary.

## Service Shape

Singleton @Injectable service that wraps all HTTP calls and exposes typed methods returning Observables.

## Method List

getAll(), getOne(id), create(dto), update(id, dto), delete(id)

## Boundary

Service owns HTTP details; components only call methods and subscribe — no URLs or HttpClient usage in components.

## Scope
Pre-lab only — do not finish the full lab in this exercise.
