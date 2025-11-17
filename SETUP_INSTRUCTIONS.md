# Setup Instructions for Snake Animation

## Step 1: Enable Workflow Permissions
1. Go to: https://github.com/solis1001/solis1001/settings/actions
2. Scroll down to "Workflow permissions"
3. Select: **"Read and write permissions"**
4. Check: **"Allow GitHub Actions to create and approve pull requests"**
5. Click **"Save"**

## Step 2: Manually Trigger the Workflow
1. Go to: https://github.com/solis1001/solis1001/actions
2. Click on **"Generate Snake Animation"** in the left sidebar
3. Click the **"Run workflow"** button (top right)
4. Select branch: **main**
5. Click **"Run workflow"** (green button)
6. Wait 1-2 minutes for it to complete

## Step 3: Verify the Output Branch
After the workflow completes:
1. Check if an `output` branch was created: https://github.com/solis1001/solis1001/branches
2. The snake animation should be at: https://github.com/solis1001/solis1001/tree/output

## Step 4: Check Your Profile
1. Go to: https://github.com/solis1001
2. The snake animation should appear at the bottom of your README

## Troubleshooting
- If the workflow fails, check the Actions tab for error messages
- Make sure workflow permissions are set correctly
- The workflow will run automatically every 6 hours after the first run

