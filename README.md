# xlmerg

A simple, powerful web-based tool for merging Excel files while preserving manual data entries. **Perfect for Vanta.com access exports and compliance workflows!**

## 🎯 **Perfect for Vanta.com Users:**

### **Weekly Access Reviews Made Easy:**
- Export access data from **Vanta.com** with updated user lists and permissions
- Preserve your **manual review entries** (conducted by, approved by, access decisions)
- Handle **new users and tools** added to your environment automatically
- Maintain **compliance audit trails** while updating system data

### **Common Vanta Workflow:**
1. **New employee joins** → Appears in fresh Vanta export
2. **New tool added** → Shows up in access export with new permissions
3. **Role changes** → Updated in Vanta but need to preserve review history
4. **xlmerg solution** → Merge new data while keeping all manual review work

## ✨ **Key Features**

- **🌐 Browser-Based** - No software installation required
- **🔑 Smart Matching** - Uses Account name as primary key
- **🔒 Data Preservation** - Blank cells don't override manual entries
- **📊 Column Mapping** - Handles Vanta export structure changes
- **🎨 Change Highlighting** - Visual feedback on what changed
- **💾 Instant Download** - Get merged file immediately
- **🔄 Repeatable** - Perfect for weekly Vanta exports

## 🚀 **Quick Start**

1. **Open:** [xlmerg live tool](https://iinaveedahmed.github.io/xlmerg) or download `index.html`
2. **Upload** your old file (with manual review entries)
3. **Upload** your fresh Vanta export
4. **Click** "Merge Files Row by Row"
5. **Download** your merged result

**That's it!** No setup, no dependencies, just works.

## 📊 **Vanta.com Usage Example**

### **Scenario: Weekly Access Review Process**

**📅 Monday: Fresh Vanta Export**
```
- New employee "Sarah Wilson" appears in AWS access
- New tool "Datadog" added to monitoring stack  
- Role changes for existing users
- Previous manual reviews need to be preserved
```

**🔄 xlmerg Process:**
1. **Old File:** `vanta_export_2025-01-15.xlsx` (with your manual reviews)
2. **New File:** `vanta_export_2025-01-22.xlsx` (fresh from Vanta)
3. **xlmerg:** Intelligent merge preserving manual data
4. **Result:** `xlmerg_20250122.xlsx` ready for continued reviews

**✅ What xlmerg Handles:**

| Change Type | Old File | New File | xlmerg Result |
|-------------|----------|----------|---------------|
| **New User** | Not present | Sarah Wilson - AWS Admin | ✅ Added as new row |
| **New Tool** | Not present | Datadog - Monitor access | ✅ Added as new sheet/section |
| **Role Update** | John: Developer | John: Senior Developer | 🔄 Role updated, reviews preserved |
| **Manual Review** | "Reviewed by: You" | "" (blank) | 🔒 Your review data preserved |
| **Access Decision** | "Access: Appropriate" | "" (blank) | 🔒 Your decision preserved |

### **Real-World Benefits:**
- **New hires** automatically appear for review
- **Tool additions** don't disrupt existing reviews  
- **Permission changes** highlighted for re-review
- **Audit trail maintained** through all changes
- **Compliance ready** with complete history

## 🔄 **Weekly Vanta Workflow**

### **Week 1: Initial Setup**
1. **Export from Vanta** → Download access report
2. **Upload to xlmerg** → Merge with any existing reviews
3. **Manual reviews** → Conduct access appropriateness reviews
4. **Save result** → Keep as baseline for next week

### **Week 2 and Beyond**
1. **Fresh Vanta export** → New users, roles, tools included
2. **Upload to xlmerg** → Old file = last week's completed reviews
3. **Auto-merge** → New data added, manual reviews preserved
4. **Review changes** → Focus only on highlighted updates
5. **Continue reviews** → Complete reviews for new/changed items

### **When New Tools/Users Added:**
- **xlmerg detects** new accounts automatically
- **Adds to review queue** with blank review fields
- **Preserves existing** completed reviews
- **Highlights changes** in existing accounts
- **No manual copying** or data loss risk

## 🧠 **How xlmerg Works**

### **Smart Merging Logic:**
- **Account name matching** - Finds same users across files
- **Column name mapping** - Handles Vanta export structure changes
- **Blank cell preservation** - Your manual entries never get overwritten
- **New data integration** - Fresh system data updates automatically

### **Data Priority Rules:**
1. **Manual review data** → Always preserved from old file
2. **System data** → Updated from new Vanta export
3. **Blank cells in Vanta export** → Don't override your manual work
4. **New accounts/tools** → Added for your review

## 📂 **File Structure**

```
xlmerg/
├── index.html     # Complete application (only file you need!)
├── README.md      # This guide
├── LICENSE        # MIT license
└── docs/          # Additional documentation
    └── user-guide.md
```

## 🔧 **Browser Compatibility**

- ✅ Chrome 80+ (Recommended)
- ✅ Firefox 75+
- ✅ Safari 13+
- ✅ Edge 80+

## 🛡️ **Security & Privacy**

- **100% local processing** - no data sent to servers
- **Vanta data stays secure** - never leaves your computer
- **No tracking** - completely private
- **Offline capable** - works without internet

## 💡 **Pro Tips for Vanta Users**

1. **Consistent naming** - Use date-based file names
2. **Weekly schedule** - Process Vanta exports same day each week
3. **Review focus** - Check highlighted changes first
4. **Backup strategy** - Keep previous weeks for audit trail
5. **Team workflow** - Share merged files for collaborative reviews

## 🆘 **Support & Issues**

- **🐛 Report Bugs:** [GitHub Issues](https://github.com/iinaveedahmed/xlmerg/issues)
- **📖 Documentation:** [User Guide](./docs/user-guide.md)
- **💬 Questions:** [GitHub Discussions](https://github.com/iinaveedahmed/xlmerg/discussions)

## 📄 **License**

MIT License - free for personal and commercial use.

---

**⭐ [Star xlmerg on GitHub](https://github.com/iinaveedahmed/xlmerg) if it saves you time!**

*Built by INATIQO PTY LTD for compliance teams who need reliable, repeatable Excel merging with zero data loss.*# Excel Row-by-Row Merger
