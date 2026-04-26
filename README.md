# EVM Ballot Unit with Thermal Printer

A visual simulation of an Electronic Voting Machine (EVM) Ballot Unit with an integrated Voter Verified Paper Audit Trail (VVPAT) thermal printer.

## Features

- **Ballot Unit Display**: Shows 13 candidate rows with serial numbers, candidate names (including Santali script support), and party symbols
- **Vote Buttons**: Each candidate row has a corresponding blue vote button with a red LED indicator
- **Status Indicator**: Green LED shows "Ready" status
- **VVPAT Printer**: Thermal printer unit that prints voter slips showing:
  - Election Commission of India branding
  - Vote confirmation message
  - Candidate name
  - Date and timestamp
- **Realistic Design**: Styled to resemble actual EVM hardware used in Indian elections

## How to Use

1. Open `index.html` in any modern web browser
2. The page displays the EVM Ballot Unit with the thermal printer below
3. The simulation is currently a static visual representation

## Technologies Used

- HTML5
- Tailwind CSS (via CDN)
- Vanilla JavaScript (for dynamic row generation)
- Custom CSS for specialized styling

## Browser Support

Works in all modern browsers including:
- Chrome
- Firefox
- Safari
- Edge
- Brave

## File Structure

```
EVM Machine/
├── index.html    # Main HTML file
└── README.md     # This file
```

## Future Enhancements

Potential improvements could include:
- Interactive voting functionality
- Dynamic candidate data loading
- Working VVPAT print simulation
- Sound effects for button presses
- Multi-language support

## Credits

Designed to simulate the EVM system used by the Election Commission of India.
