The `SampleDataModule` is a nice exmple of the different layers explained. It holds some components (representing the *components* layer) and also has a `SampleDataService` (representing the *service* layer) which is imported in the required components.

The service acts as the adapter element explained earlier (used to make XHR calls). 