![banner](https://github.com/d0lfyn/opencity3d/assets/13762069/26e169b9-2794-45e0-92b4-4599e959dc65)

# opencity3d

This project provides a standard for creating, sharing, and printing modular 3D models of urban environments. It encompasses considerations of scale, physical connectors, and best practices.

## Objectives

- **Build a platform**, by facilitating reuse and interoperability in the design and printing of hobby kits.
- **Nurture a community**, by enabling collaboration and exchange among those interested in 3D printing cities.
- **Craft cities**, by using 3D technologies to bring concepts into reality.

## How to use the standard

The standard is maintained in versions, each consisting of several components: specifications, printable connectors, and printer configurations. All of this is documented in the wiki knowledge base.

- Specifications can be found in (VERSION)/specs. Therein are documents of scale and physical connector design.
- Printable connectors can be found in (VERSION)/prints. Therein are files for grids, building bases, and adapters.
- Printer configurations can be found in (VERSION)/printers. Therein are presets for various printers.
- The wiki knowledge base documents the standards project.

To use the standard, you need designs to print, as well as access to a 3D printer. You can either create your own files from scratch or use existing ones from public and/or private source. Given that you have designs on hand:

1. Scale the designs per the spec version of your choice, found in (VERSION)/specs.
2. From (VERSION)/prints, choose appropriately-sized bases for your scaled designs, and in your choice of 3d modeling software, merge the respective mesh underneath each design.
3. Also from (VERSION)/prints, choose adapters corresponding to each base, as well as a grid large enough to mount the building and adapter assemblies for your designs.
4. Prepare the files for 3D printing using any 3D printing software. If available, choose printer configurations from (VERSION)/printers to possibly streamline the process.
5. Print. Experimentation will likely be required, as tolerances depend on each printer setup. The standard minimises wasted resources, inasmuch as only adapters need to be re-printed.

## How to contribute to the project

This project is open-source and welcomes contributions from anyone who is interested in 3D printing cities. There are several ways you can contribute to the project:

- You can report issues or suggest enhancements on the GitHub issue tracker.
- You can join the community chat with feedback, questions, gallery submissions, printer configurations, &c. on the GitHub Discussions forum.

## License

This project is licensed under the MIT License - see the LICENSE file for details.
