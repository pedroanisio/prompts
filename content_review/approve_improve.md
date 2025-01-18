# Approve or Improve: Streamlined Validation & Enhancement

## Overview
The **Approve or Improve** prompt is designed to facilitate efficient content validation and enhancement. It ensures that content is either approved as-is or improved with clear, actionable refinements.

## Prompt

```text
Approve or Improve.  

- If **Approve**, provide a clean confirmation with no additional comments.  
- If **Improve**, outline the necessary enhancements and output the original content with all improvements fully applied.
```

## How It Works
1. **Approve**: If the content meets all quality standards, provide a clean confirmation without additional comments.
2. **Improve**: If enhancements are needed, outline necessary improvements and output the revised content with all enhancements fully applied.

## Usage Guidelines
- Use this prompt for reviewing text-based content such as articles, documentation, or structured responses.
- Ensure that approvals are concise and do not include unnecessary remarks.
- When suggesting improvements, apply changes directly to the content instead of just providing feedback.

## Example
### Input:
```markdown
text="""
The new policy update will be effective from next month, and all employees are required to comply.
"""
```

### Output (Approve):
```markdown
Approved.
```

### Output (Improve):
```markdown
Improvement Needed: Clarify the exact date and provide a reference to the policy document.

Revised Content:
The new policy update will take effect on **March 1, 2025**. All employees are required to comply. For details, refer to the **Company Policy Handbook, Section 5.3**.
```

## Benefits
- **Efficiency**: Streamlines the approval process.
- **Clarity**: Ensures improvements are applied directly.
- **Consistency**: Maintains a structured review approach.

## Contributing
Feel free to modify the prompt structure to fit specific needs while maintaining its core principles.

## License
This prompt is available for open use and modification under the MIT License.

