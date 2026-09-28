# bedfilcr
Minecraft Bedrock CLI for generating individual entity, block and item files


bedfilcr

Minecraft Bedrock CLI for generating individual entity, block, and item files.

bedfilcr is a lightweight interactive CLI for creating Minecraft Bedrock Edition JSON files with customizable components.

Features

- Generate individual entity, block, and item files
- Interactive component selection
- Configure component values
- Add extra component properties
- Simple CLI workflow
- Lightweight package

Usage

Run:

npx bfc

The CLI will guide you through:

1. Entering the file name
2. Choosing the maximum number of components
3. Selecting components
4. Entering required component values
5. Adding optional extra properties
6. Choosing the output directory
7. Generating the JSON file

Example

For an entity, you can select components such as:

"minecraft:health": {
  "value": 28,
  "max": 28
},
"minecraft:movement": {
  "value": 0.32
}

bedfilcr then generates the corresponding Bedrock JSON file.

Current Limitation

bedfilcr currently generates individual Bedrock files.

It does not currently generate a complete ".mcpack" or full addon package.

Dependencies

- "@minecraft/creator-tools"
- "@minecraft/bedrock-schemas"
- "chalk"
- "inquirer"
- "uuid"

Future Plans

Planned improvements include:

- JavaScript writing support
- Stronger validation
- Better error detection and reporting
- Additional Bedrock component support

## License

MIT License
